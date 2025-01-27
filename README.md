# Retail Store Simulation and Optimization with SimPy

## Project Overview
This project simulates and optimizes customer behavior, cashier processes, queue management, and inventory management in a retail store using **SimPy**. The simulation models realistic store operations, including dynamic customer shopping patterns, queue selection, cashier workflows with breaks, and automated inventory restocking. The collected data provides insights for improving customer flow, resource allocation, and inventory management.

## Key Features
- **Customer Behavior Simulation**: Models customer arrivals, shopping times, checkout durations, and queue selection.
- **Cashier Workflow Management**: Includes break management and resource allocation for regular and express checkout counters.
- **Dynamic Queue Selection**: Customers select queues based on their cart size (express or regular).
- **Inventory Management**: Tracks stock levels, simulates sales, and automates restocking when thresholds are reached.
- **Scenario Testing and Optimization**: Configurable parameters to test different store setups and analyze performance.
- **Comprehensive Data Collection**: Tracks wait times, checkout times, sales, and stock shortages for analysis.

## Steps and Implementation

### **Step 1: Basic Simulation Setup**
- Created a basic simulation to model customer arrivals and checkout.
- Simulated random checkout durations and recorded customer flow.

### **Step 2: Detailed Customer Modeling**
- Enhanced customer behavior to include shopping time and variable item counts.
- Improved checkout duration calculations.

### **Step 3: Queue Management System**
- Introduced dynamic queue selection based on the number of items in the cart.
- Added express checkout lanes for customers with fewer items.

### **Step 4: Cashier and Staff Management**
- Simulated cashier workflows, including working durations and break times.
- Managed express and regular cashier operations.

### **Step 5: Inventory Management**
- Integrated inventory tracking for multiple products.
- Automated restocking when stock levels fell below a threshold.

### **Step 6: Data Collection and Analysis**
- Collected data on wait times, checkout durations, sales, and stock shortages.
- Performed analysis to identify trends and optimize operations.

### **Step 7: Scenario Testing and Optimization**
- Designed a flexible simulation function to test different scenarios by adjusting:
  - Number of cashiers.
  - Customer arrival rates.
  - Inventory settings.
- Analyzed results to recommend optimal configurations.

### **Final Consolidation**
- Combined all steps into a unified simulation model.
- Enabled comprehensive analysis with detailed output for operational insights.

## Outputs
- **Wait Times**: Average customer wait time at each checkout.
- **Checkout Times**: Average time spent at checkout.
- **Sales Data**: Total sales for each product.
- **Stock Shortages**: Frequency of stockouts for each product.
- **Restocking Logs**: Recorded restocking events to ensure adequate inventory levels.

## Example Output
- Average checkout time: **1.98 seconds**
- Sales:
  - Product A: **1267 units**
  - Product B: **1295 units**
  - Product C: **1341 units**
- Restocking Logs:
  - Product A: **Restocked multiple times during peak hours**
  - Product B: **Handled high demand with timely restocks**
