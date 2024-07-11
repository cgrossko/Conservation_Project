**Conservation Dataset Analysis**

**Introduction**

This project analyzes a conservation dataset that includes information about various species observed in different parks. The analysis focuses on understanding the distribution of conservation statuses, identifying species more likely to be endangered, and visualizing species observations across parks.

**Datasets**

Observations Dataset (observations.csv)

**Columns:**

scientific_name: Scientific name of the species

park_name: Name of the park where the species was observed

observations: Number of observations of the species in the park

Species Information Dataset (species_info.csv)

**Columns:**

category: Category of the species (e.g., Mammal, Bird, Vascular Plant, etc.)

scientific_name: Scientific name of the species

common_names: Common names of the species

conservation_status: Conservation status of the species (e.g., Endangered, Species of Concern, etc.)

**Data Cleaning**

Entries labeled as 'Vascular Plant' in the category column were removed from the dataset to focus the analysis on animals.

**Analysis and Visualizations**

1. Distribution of Conservation Status for Animals
Objective: To understand the distribution of conservation statuses among the observed species.
Visualization: A bar chart showing the count of each conservation status category.

3. Endangered Species by Category
Objective: To identify which types of species (categories) are more likely to be endangered.
Visualization: A bar chart showing the count of endangered species within each category.

5. Most Observed Species at Each Park
Objective: To determine which species were spotted the most in each park.
Visualization: A bar chart for each park showing the species with the highest number of observations.

7. Conservation Status by Park
Objective: To visualize the conservation status distribution across different parks.
Visualization: A series of bar charts or a grouped bar chart showing the conservation status distribution for each park. Data points are included for clarity.

**Conclusion**

The analysis provides insights into the conservation status of various species observed in different parks. By understanding which species are more likely to be endangered and their distribution across parks, conservation efforts can be better directed.
