# Data Dictionary

## Orders (`data/Orders.xlsx`)

| Field                       | Description                                                                             |
|-----------------------------|-----------------------------------------------------------------------------------------|
| Order ID                    | Unique identifier for each order                                                        |
| Actual Delivery Date        | Date the delivery actually occurred                                                     |
| Delay Reason                | Cause of delay (e.g. weather, vehicle breakdown, hub bottleneck) — blank if not delayed |
| Driver ID / Driver Name     | Driver who fulfilled the order — links to `Drivers`                                     |
| Hub Name                    | Hub that processed/dispatched the order — links to `Hubs`                               |
| Is Delayed / Is On Time     | Boolean flags for SLA adherence                                                         |
| Order Date                  | Date the order was placed                                                               |
| Order Status                | Delivered / Cancelled                                                                   |
| Vehicle Name / Vehicle Type | Vehicle used and its category — links to `Vehicles`                                     |
| Customer Satisfaction Score | Post-delivery customer rating                                                           |
| Delivery Time Hours         | Total time from order to delivery                                                       |
| Hub Processing Time Hours   | Time the hub took to process the order before dispatch                                  |                

## Hubs (`data/Hubs.xlsx`)

| Field        | Description                                          |
|--------------|------------------------------------------------------|
| Hub ID       | Unique identifier for each hub                       |
| Hub Name     | Hub's display name / location                        |
| Hub Capacity | Maximum orders the hub can process in a given period |

## Drivers (`data/Drivers.xlsx`)

| Field              | Description                       |
|--------------------|-----------------------------------|
| DriverID           | Unique identifier for each driver |
| DriverName         | Driver's display name             |
| Employment Type    | Full-time / Part-time / Contract  |
| Hire Date          | Date the driver joined            |
| Experience Years   | Years of driving experience       |
| Performance Rating | Internal performance score        |

## Vehicles (`data/Vehicles.xlsx`)

| Field                     | Description                                |
|---------------------------|--------------------------------------------|
| Purchase Date             | Date the vehicle was acquired              |
| Vehicle ID / Vehicle Code | Unique identifier for each vehicle         |
| Vehicle Model             | Make/model of the vehicle                  |
| Vehicle Status            | Active / Maintenance                       |        
| Breakdown                 | Number of recorded breakdowns              |
| Maintenance count Alert   | Whether a maintenance event is flagged/due |
