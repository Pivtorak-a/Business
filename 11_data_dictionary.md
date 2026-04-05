# Data Dictionary

## Мета

Цей файл — основа під майбутню фінансово-операційну модель.  
Тут зафіксовані поля, які треба буде зібрати по кожному напряму.

## Universal fields

- direction_name
- month
- scenario_name
- price_purchase
- price_sale
- volume
- volume_unit
- transport_cost
- labor_cost
- storage_cost
- fixed_cost
- variable_cost
- gross_margin
- net_margin
- working_capital_lock_days
- capex_need
- asset_utilization_percent

## Apple

- point_id
- point_rent
- avg_daily_tons
- avg_supplier_batch_kg
- max_storage_hours
- collection_km
- diesel_per_ton
- spoilage_percent
- buyer_delay_days

## Firewood

- raw_wood_purchase_price
- processing_cost
- moisture_loss_percent
- storage_months
- average_delivery_km
- sales_unit_type
- average_sale_volume

## Salt

- salt_purchase_price
- inbound_transport_cost
- storage_loss_percent
- storage_months
- winter_markup_percent
- covered_storage_required_area
- locked_capital_days

## Aggregates

- sku_name
- purchase_ton_price
- delivered_purchase_ton_price
- average_order_tons
- average_delivery_km
- stock_turn_days
- loader_need_flag

## Logistics

- vehicle_id
- vehicle_type
- payload_tons
- fuel_norm
- repair_reserve_per_month
- external_rate_per_trip
- internal_transfer_value
- idle_days
- utilization_percent

## Shared resources

- yard_area_total
- yard_area_free
- diesel_budget
- available_cash
- vehicle_hours_available
- operator_hours_available
- owner_hours_available
