# Lean Notes

## Week 2: Understanding Flow
-------------------------------------------------------------------------------

### Capacity Analysis
 * Process Mapping
 	- Identifying steps and processes
 	- inputs
 	- outputs
 	- controls
 * Focus on entire system now, not just steps
 * what is a business process?
 	- Repeatable coherent set of activities
 	- consumes resources
 	- clear input
 	- certain material or immaterial outputs
 	- for customers (internal / external)
 	- not one off, repeats often as business runs
 * Transforms inputs to outputs via resources
 * How to make PFD?
 	- Arrange into flow
 	- triangle for storage
 	- rectangle for processes

### Finding the bottleneck - Part 1

* Process Capacity = Max number of units produced per unit of time
* How to measure?
	- Materials going in
	- Resources turn materials into products
	- Demand (If no demand, don't make anything)
	- Capacity focuses on the second point
* Eg for skate board
	- 5min for assembly
	- 4min for sand
	- 6min for paint
	- **15min Total**
* If no inventory, its a sequential process
* Fords focus was on speed

#### Definitions

* Processing Time = p = (4/5/6) = Time it takes for an activity to process one flow unit
* Flow Time = (15min) = Time to process a unit through the process.
* Resource Capacity = 1/p, max N per unit time
	- If there are m resources then its m/p
	- Capacity Example
		- Assembly: 1 / 5 = 12 boards per hour
		- Sand: 1 / 4 = 15 boards per hour
		- Paint: 1 / 6 = 10 boards per hour **BOTTLENECK**
* Process Capacity  = Minimum resource capacity in the process
	- Bottlneck, slowest process
* Process Capacity = bottleneck capacity
* Flow rate = Process Capacity assuming enough raw materials and we can sell every skateboard we make
* Resource Utilization = Flow Rate / Resource Capacity

### Finding the bottleneck - Part 2

* Resource utilisation
* Cannot be >100%
* Example:
	- Assembly: 10 / 12 = 83%
	- Sand: 	10 / 15 = 66%
	- Paint: 	10 / 10 = 100% 
* Focus needs to be on high utilization resources
* Low utilized assets have idle time

### Finding the bottleneck - Example

* Another example of capacity analysis
* Assume
* Chair factory
	- Base = 6 min
	- Upholstery = 10 min
	- Assembly = 8 min
* Flow unit = 1 office chair
* Flow time = 24 min
* Capacity
	- Base = 		1 / 6 	= 10 units/h
	- Upholstery = 	1 / 10 	= 6 units/h
	- Assembly = 	1 / 8 	= 7.5 units/h
* Process Capacity = 6 units/h
* Flow Rate = 6 units/h (becuase unconstrained at either market or material side)
* Resource Utilisation
	- Base = 		6 / 10 	= 60%
	- Upholstery = 	6 / 6 	= 100%
	- Assembly = 	6 / 7.5 = 80%
* Their is idle time in Base and Assembly steps