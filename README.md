# XpertCalc

🚀 **XpertCalc** is an advanced engineering and industrial calculation tool designed to help professionals, engineers, and students perform complex calculations across various fields. This project provides code implementations for calculating parameters related to mechanical, structural, hydraulic, electrical, and energy systems.

## 📌 Features
### **1. Finance & Business**
- **EMI Calculator** – Calculates loan EMI based on interest and tenure.
- **GST Calculator** – Computes GST-inclusive and exclusive prices.
- **Stock Profit/Loss Calculator** – Helps investors calculate gains or losses.
- **Freelancer Income Calculator** – Estimates income after tax and expenses.

### **2. Science & Engineering**
- **Ohm’s Law Calculator** – Calculates voltage, current, or resistance.
- **Force & Motion Calculator** – Computes force, acceleration, and momentum.
- **Heat Transfer Calculator** – Estimates heat transfer in physics experiments.
- **Electrical Circuit Calculator** – Calculates power, resistance, and current in circuits.

### **3. Agriculture**
- **Fertilizer Requirement Calculator** – Suggests the right amount of fertilizers for crops.
- **Irrigation Water Requirement Calculator** – Helps farmers decide how much water to use.
- **Crop Yield Estimator** – Predicts crop yield based on input parameters.

### **4. Education & Learning**
- **GPA/CGPA Calculator** – Computes GPA from grades.
- **Unit Conversion Calculator** – Converts metric and imperial units.
- **Physics Formula Calculator** – Solves physics equations with inputs.
- **Probability & Statistics Calculator** – Computes mean, median, mode, and probability values.

### **5. Health & Fitness**
- **BMI Calculator** – Calculates Body Mass Index.
- **Calorie Intake Calculator** – Estimates daily calorie needs.
- **Heart Rate Calculator** – Suggests optimal heart rate for workouts.
- **Sleep Cycle Calculator** – Helps plan a proper sleep schedule.

### **6. Daily Life & Utility**
- **Age Calculator** – Finds exact age in years, months, and days.
- **Bill Splitter** – Splits bills among friends with tips included.
- **Travel Cost Calculator** – Estimates fuel or transportation costs.
- **Cooking Measurement Converter** – Converts cups to grams, liters to milliliters, etc.

### **7. Industrial & Engineering Calculations**
- **Belt Conveyor Design** (Length, Load, Motor Power, Speed, etc.)
- **Structural Load Calculation** (Beam Strength, Shear Force, Bending Moment, etc.)
- **HVAC Load Analysis** (Cooling & Heating Load, Airflow, Duct Sizing, etc.)
- **Hydraulic System Calculations** (Flow Rate, Pressure, Pump Sizing, etc.)
- **Solar Panel System Design** (Energy Estimation, Panel Sizing, Battery Selection, etc.)

## 📁 Project Structure
```
XpertCalc/
│── calculators/
│   ├── finance/
│   │   ├── emi_calculator.js
│   │   ├── gst_calculator.js
│   │   ├── stock_profit_calculator.js
│   │   ├── freelancer_income_calculator.js
│   ├── science/
│   │   ├── ohms_law.js
│   │   ├── force_motion.js
│   │   ├── heat_transfer.js
│   │   ├── electrical_circuit.js
│   ├── agriculture/
│   │   ├── fertilizer_calculator.js
│   │   ├── irrigation_water.js
│   │   ├── crop_yield.js
│   ├── education/
│   │   ├── gpa_calculator.js
│   │   ├── unit_conversion.js
│   │   ├── physics_formula.js
│   │   ├── probability_stats.js
│   ├── health/
│   │   ├── bmi_calculator.js
│   │   ├── calorie_intake.js
│   │   ├── heart_rate.js
│   │   ├── sleep_cycle.js
│   ├── daily_life/
│   │   ├── age_calculator.js
│   │   ├── bill_splitter.js
│   │   ├── travel_cost.js
│   │   ├── cooking_converter.js
│   ├── industrial/
│   │   ├── belt_conveyor.js
│   │   ├── structural_load.js
│   │   ├── hvac_load.js
│   │   ├── hydraulic_system.js
│   │   ├── solar_panel.js
│── tests/
│── docs/
│── examples/
│── LICENSE
│── README.md
```

## 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/XpertCalc.git
   cd XpertCalc
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run an example calculation:
   ```bash
   node calculators/finance/emi_calculator.js
   ```

## 📚 Usage
Each module can be used independently. Example for **EMI Calculation**:
```javascript
const { calculateEMI } = require('./calculators/finance/emi_calculator');

const emi = calculateEMI(500000, 7.5, 60);
console.log(`Monthly EMI: ${emi}`);
```

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
We welcome contributions! Feel free to open an issue or submit a pull request.

## 📬 Contact
For queries, reach out via GitHub Issues or email at `your-email@example.com`.
