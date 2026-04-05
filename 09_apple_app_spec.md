# Apple App Specification

## Known facts

По додатку вже зафіксовано наступне:

- додаток створюється для **керування мережею мобільних точок прийому технічного яблука**;
- має бути **автоматичний розрахунок собівартості партій**;
- мають бути **правила перенесення збиткових точок**;
- операційним адміністратором планується **дружина**;
- і користувач, і дружина мають бачити **усі ключові показники**.

## Роль додатку

Це не "записник".  
Це має бути операційний центр, який:

- показує, які точки працюють;
- показує, які партії вигідні;
- підказує, які точки тягнуть систему вниз;
- підтримує рішення по маршрутах, перенесенню та завантаженню.

## Мінімальні сутності

### Point
- point_id
- name
- location
- status
- open_date
- close_date
- operator
- rent
- daily_capacity_estimate

### Batch
- batch_id
- point_id
- gross_weight
- purchase_price
- purchase_total
- loading_time
- dispatch_time
- transport_unit
- transport_cost
- losses
- final_net_cost
- buyer_price
- buyer_total
- net_margin

### Route
- route_id
- date
- vehicle_id
- origin
- destination
- km
- fuel_cost
- total_time
- load_utilization

### Vehicle
- vehicle_id
- type
- payload_limit
- fuel_norm
- status

## Мінімальні дашборди

1. Points dashboard
- active points
- tons per point
- margin per point
- diesel per ton
- waiting time
- candidate points to relocate

2. Batches dashboard
- batch profitability
- average cost per ton
- time to dispatch
- losses

3. Logistics dashboard
- route cost
- km per day
- load utilization
- fuel per ton

4. Finance dashboard
- purchase spend
- received cash
- locked cash
- margin
- cash gap risk

## Майбутні правила

- якщо точка стабільно нижча за мінімальний тоннаж — флагнути;
- якщо route cost на тонну перевищує поріг — флагнути;
- якщо партія довго чекає відправки — флагнути;
- якщо point margin негативна — кандидат на перенесення.

## Що ще треба визначити

- платформа: desktop / mobile / web;
- ролі доступу;
- офлайн режим;
- хто і як вводить вагу;
- інтеграція з вагами;
- експорт у Excel;
- статуси партій;
- довідник покупців;
- журнал рішень про перенесення точки.
