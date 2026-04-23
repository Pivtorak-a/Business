# Structured Notes

## Core idea

This repository describes not a single isolated business, but a seasonal trading and logistics system built around shared resources:

- a material and logistics yard of about 0.4 ha;
- transport and special equipment;
- working capital;
- operator and owner attention;
- weighing, accounting, dispatching and storage discipline.

The main management problem is not only whether each direction is profitable on paper, but whether the system can allocate cash, yard space, vehicles and attention at the right time of year.

## Business directions

### 1. Technical apple for concentrate

Role: seasonal fast-cash direction with high operational intensity.

Known facts:

- model: mobile collection points for technical apple;
- base configuration: 1 main transshipment yard plus 3 mobile collection points;
- main base area mentioned separately: 4,000 m2;
- mobile points are for collection and short storage up to 48 hours;
- last season there was a reliable buyer who paid without delay;
- factories-buyers were easy to find;
- main problem was operations, not demand.

Main risks:

- small batches of 100-500 kg create high collection cost;
- vans could carry no more than 3 tons;
- direct address collection used too much diesel and time;
- delays create quality and weight-loss risk;
- weak points may consume transport and attention without enough tonnage.

Required management logic:

- define minimum profitable batch and minimum daily tonnage per point;
- track diesel per ton and route cost per ton;
- decide when to move or close a weak point;
- prioritize direct large batches and fast dispatch.

### 2. Firewood

Role: winter cash-flow direction and potential B2C/B2B side line.

Known facts:

- legal model considered: FOP group 2;
- seasonality: summer procurement, winter sales;
- can use the same yard, storage, delivery and customer base logic.

Open questions:

- type of firewood;
- sales unit;
- raw material source and purchase price;
- cutting and splitting cost;
- storage and drying losses;
- target geography and delivery economics.

### 3. Technical salt

Role: winter B2B/B2C stock business with strong working capital and storage requirements.

Known facts:

- legal model considered: FOP group 3;
- connected to the 0.4 ha yard model;
- spring purchase and winter sale logic;
- covered storage is required;
- quality depends heavily on storage.

Main risks:

- buying too early or too expensively;
- freezing too much working capital;
- not having enough covered storage;
- overestimating winter demand;
- undercounting delivery and handling cost.

### 4. Aggregates and building materials

Role: likely base permanent direction for the yard.

Known facts:

- includes sand, crushed stone, screenings and other bulk materials;
- works through B2C and B2B;
- start model is an rented yard;
- needs rational surface: backfill, two key asphalt/concrete zones and separate salt canopy;
- can cooperate even with competitors through product or logistics.

Strategic value:

- loads the yard daily;
- creates repeated customer demand;
- combines naturally with delivery;
- can become the platform for scaling.

Open questions:

- exact starting SKU list;
- minimum stock per SKU;
- purchase sources and prices;
- margin per fraction;
- B2B/B2C split;
- delivery radius and real margin after delivery.

### 5. Transport and logistics

Role: the nervous system of the project and possibly a separate profit center.

Known facts:

- first target asset: manipulator around 20,000 USD;
- next possible asset: truck around 15,000 USD;
- owner has B, C, C1, CE categories;
- portable weighing system concept is already selected;
- logistics must serve both internal directions and external paid jobs.

Key rule:

The same vehicle cannot simultaneously serve apple collection, salt delivery, customer trips and yard operations. Therefore every vehicle decision must include opportunity cost.

## Shared constraints

### Working capital

Cash can be locked in salt, firewood or inventory exactly when another direction needs launch capital. The plan must manage cash month by month, not only annual profit.

### Yard area

The yard must balance:

- bulk material zones;
- salt covered storage;
- firewood storage;
- turning area for equipment;
- temporary storage;
- loading and unloading.

### Equipment

Equipment is both infrastructure and revenue source. Its value should be measured through:

- internal utilization;
- external utilization;
- idle days;
- fuel cost;
- repair reserve;
- contribution margin.

### People and attention

The owner and administrator time is a real bottleneck, especially during apple season and winter sales peaks.

### Weighing and accounting

Weight control is critical for purchases, sales, disputes, stock control and true margin calculation.

## Seasonality map

### Spring

- buy technical salt if price and storage are favorable;
- prepare yard surface and covered storage;
- prepare supplier and buyer lists;
- prepare data model and price monitoring.

### Summer

- procure and prepare firewood;
- run active building materials sales;
- prepare logistics assets;
- prepare mobile apple collection system.

### Autumn

- run technical apple season;
- focus on fast dispatch and route discipline;
- protect transport from overload and idle waiting;
- collect real operational data for the simulator.

### Winter

- sell salt;
- sell firewood;
- use logistics for delivery and paid jobs;
- review year results and prepare next cycle.

## Priority order from the notes

1. Apple: highest operational priority because it already has market validation and clear pain points.
2. Logistics: critical because every other direction depends on it.
3. Aggregates: best candidate for permanent base direction.
4. Salt: strong seasonal opportunity but needs careful cash and storage control.
5. Firewood: useful winter cash-flow direction, but data gaps are still large.
6. General simulator: needed to compare all directions through shared constraints.

## Data gaps to close first

- purchase and sale prices by month for each direction;
- minimum profitable batch/order size;
- real fuel cost per ton or per trip;
- average loading/unloading time;
- storage loss and quality-loss percentages;
- working capital lock period;
- fixed monthly yard and equipment costs;
- capacity of the yard by zone;
- vehicle availability and cost per hour/day;
- B2B/B2C customer mix;
- legal and tax implications before scaling.