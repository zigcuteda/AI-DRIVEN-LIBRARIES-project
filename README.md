# AI-DRIVEN-LIBRARIES-project
Semester 2 AI DRIVEN LIBRARIES with Python Project (pandas library used)


## Data Source and Collection

The data used in this project consists of secondary quantitative data collected from reliable and publicly available online sources. As permitted under the project guidelines, Google Forms were not used. Instead, vehicle specification data was obtained from authenticated automobile websites and official manufacturer resources.

The dataset includes specifications of 102 transport vehicles, covering variables such as physical dimensions, weight, engine capacity, displacement, wheelbase, ground clearance, and boot space. Reputed platforms including Autocar India, CarDekho, V3Cars, CarAndBike, along with official manufacturer websites and brochures, were referenced to ensure accuracy and authenticity.

Each data entry is supported by a corresponding reference link, documented separately to maintain transparency and verifiability. The collected data was compiled into a CSV file and processed using Python in the Google Colab environment for further analysis.

---

## Dataset Columns

- COMPANY NAME  
- TYPE  
- SUB TYPE  
- NAME  
- HEIGHT (IN CM)  
- WIDTH (IN CM)  
- LENGTH (IN CM)  
- WEIGHT (IN KG)  
- WHEELBASE (IN CM)  
- ENGINE (IN LTR)  
- DISPLACEMENT (IN CC)  
- GROUND CLEARANCE (IN CM)  
- BOOT SPACE (IN LTR)  

---

## Column Description

### 1. COMPANY NAME
Represents the manufacturer or brand of the vehicle.  
Examples: Maruti Suzuki, Hyundai, BMW, Audi  
Used for brand-wise comparison and grouping.

### 2. TYPE
Indicates the broad vehicle category.  
Examples: Hatchback, Sedan, SUV, Coupe  
Helps in segment-level analysis.

### 3. SUB TYPE
Provides a more specific classification within the main type.  
Examples: Compact SUV, Luxury Sedan, Sports Hatchback  
Useful for fine-grained segmentation.

### 4. NAME
Represents the model name of the vehicle.  
Examples: Swift, City, X5  
Acts as the primary identifier for each car.

### 5. HEIGHT (IN CM)
Vertical height of the vehicle measured from ground to roof.  
Influences headroom, aerodynamics, and overall stance.

### 6. WIDTH (IN CM)
Horizontal width of the vehicle, excluding mirrors.  
Affects cabin space, road presence, and stability.

### 7. LENGTH (IN CM)
Overall length of the vehicle.  
Useful for segment classification and parking feasibility analysis.

### 8. WEIGHT (IN KG)
Kerb weight of the vehicle.  
Impacts fuel efficiency, performance, and handling characteristics.

### 9. WHEELBASE (IN CM)
Distance between the front and rear wheels.  
A longer wheelbase generally improves ride comfort and rear legroom.

### 10. ENGINE (IN LTR)
Engine capacity measured in litres (e.g., 1.2L, 2.0L).  
Indicates performance potential.  
Not applicable for electric vehicles.

### 11. DISPLACEMENT (IN CC)
Engine displacement measured in cubic centimeters.  
Provides a precise measure of engine size and is often used for taxation and performance comparison.  
Not applicable for electric vehicles.

### 12. GROUND CLEARANCE (IN CM)
Distance between the lowest point of the vehicle and the ground.  
Critical for driving conditions on Indian roads and off-road capability.

### 13. BOOT SPACE (IN LTR)
Luggage or cargo storage capacity of the vehicle.  
Useful for evaluating practicality and family usage.  
Not applicable for certain vehicle types such as pickup trucks.

---

## About the Dataset

This dataset is a structured combination of quantitative and categorical variables representing passenger vehicles. It captures manufacturer details, vehicle segmentation, physical dimensions, engine specifications, and utility features. The dataset is designed to support comparative analysis, classification tasks, and performance-based evaluation across different manufacturers and vehicle segments.

---

## Purpose and Applications of the Dataset

The dataset enables analysis and comparison of passenger vehicles across manufacturers and segments by integrating categorical attributes (company, type, sub-type, and model) with quantitative specifications (dimensions, weight, engine capacity, displacement, ground clearance, and boot space).

It supports brand-wise and segment-wise comparisons, helping identify how manufacturers position their vehicles in terms of size, performance potential, and practicality. The data can be used for market analysis, understanding segment dominance, identifying design trade-offs such as engine size versus weight, and evaluating utility differences such as boot space across brands.

Additionally, the dataset is suitable for classification, trend identification, and decision-support applications, providing valuable insights for consumers, researchers, analysts, and automotive planners.

---

## Software and Tools Used

- **Google Colaboratory**  
  Cloud-based interactive notebook environment used to write, execute, and document Python code without local setup.

- **Python Programming Language**  
  Used for data cleaning, manipulation, analysis, and visualization.

- **Pandas Library**  
  Utilized for data preprocessing, handling missing values, grouping, aggregation, and statistical analysis.

- **NumPy Library**  
  Used for numerical computations and efficient handling of arrays and mathematical operations.

- **Matplotlib Library**  
  Employed for creating visualizations such as bar charts, scatter plots, and stacked bar charts.

- **Seaborn Library**  
  Used for advanced statistical visualizations including box plots and correlation heatmaps.
