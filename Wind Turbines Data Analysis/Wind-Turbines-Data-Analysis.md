## Introduction

The influence of wind energy as a renewable source of energy has been
advocated considerably for the past decades. The method of harvesting
energy from the wind is through what are known as wind turbines. Wind
turbines are self explanatory, they’re turbines that have large vaned
wheels rotated by the wind to generate electricity. Wind turbines also
have a certain capacity that they’re able to generate, but what
components of turbines, if any, are directly correlated to the turbine
capacity? <br><br> ![A clipart of three wind turbines. The source of the
image can be found in the conclusion under
references](wind_turbines.png) <br><br> We will be exploring that
question by analyzing turbine data that was gathered from the Federal
Aviation Administration’s (FAA) Digital Obstacle File (DOF) and
Obstruction Evaluation Airport Airspace Analysis (OE-AAA), the American
Clean Power Association (ACP), Lawrence Berkeley National Laboratory
(LBNL), and the United States Geological Survey (USGS). According to the
United States Wind Turbine Database (USWTDB), the data for technical
specifications for turbines were assigned based on the wind turbine make
and models as provided by manufacturers and project developers directly,
and via FAA datasets, information on the wind project developer or
turbine manufacturer websites, or other online sources. What we’re
interested in from this data is the quantitative variable called
“Turbine.Capacity”, which tells us the electrical generation capacity of
the turbine measured in KW (kilo-watts), and we’ll call that our outcome
variable. We’ll be comparing our outcome variable to three other
quantitative variables, namely “Turbine.Hub\_Height”,
“Turbine.Rotor\_Diameter”, and “Turbine.Swept\_Area”, and we’ll call
those our predictor variables. “Turbine.Hub\_Height” tells us the height
in meters of the turbine’s hub, “Turbine.Rotor\_Diameter” tells us the
diameter in meters of the turbine’s rotor, and “Turbine.Swept\_Area”
tells us the area swept in each rotation of the turbine’s rotor. We’ll
begin by analyzing the univariate distributions of our outcome variable
and predictor variables. Then, we’ll analyze the bivariate distributions
of our outcome variable to each of the predictor variables. Finally,
we’ll conclude our findings by comparing the relationships between the
outcome variable and the predictor variables.

## Univariate Distributions

### Outcome Variable

![Figure 1: Histogram distribution of electricity generation capacity
(in kilowatts) for wind turbines. The capacity ranges from 50 to 6000
kW. The long dashes represent the mean, while the short dashes represent
+1 and -1 standard deviation of the
mean.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-2-1.png)

There are 63961 wind turbines. The distribution of turbine capacity is
unimodal and approximately symmetric, with a mean of 1945.3 and a
standard deviation of 689.73. There is also a potential outlier at 6000
kW turbine capacity.

### Predictor Variables

![Figure 2: Histogram distribution of hub height (in meters) for wind
turbines. The hub height ranges from 22.8 to 131 m. The long dashes
represent the mean, while the short dashes represent +1 and -1 standard
deviation of the
mean.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-3-1.png)

The distribution of turbine hub height is unimodal and approximately
symmetric, with a mean of 80.27 and a standard deviation of 12.47.

![Figure 3: Histogram distribution of rotor diameter (in meters) for
wind turbines. The rotor diameter ranges from 14 to 155 m. The long
dashes represent the mean, while the short dashes represent +1 and -1
standard deviation of the
mean.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-4-1.png)

The distribution of turbine rotor diameter is unimodal and approximately
symmetric, with a mean of 94.68 and a standard deviation of 23.45.

![Figure 4: Histogram distribution of swept area for wind turbines. The
swept area ranges from 153.94 (min) to 18869.19 (max). The long dashes
represent the mean, while the short dashes represent +1 and -1 standard
deviation of the
mean.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-5-1.png)

The distribution of turbine swept area is bimodal and approximately
symmetric, with a mean of 7472.67 and a standard deviation of 3267.17.

## Bivariate Relationships

![Figure 5: Scatterplot distribution between hub height (in meters) and
electricity generation capacity (in kilowatts) for wind turbines. The
line of best fit has been
included.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-6-1.png)

There is a positive, strong, and linear relationship between turbine hub
height and turbine capacity, with a correlation coefficient of 0.72.

![Figure 6: Scatterplot distribution between rotor diameter (in meters)
and electricity generation capacity (in kilowatts) for wind turbines.
The line of best fit has been
included.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-7-1.png)

There is a positive, very strong, and linear relationship between
turbine rotor diameter and turbine capacity, with a correlation
coefficient of 0.88

![Figure 7: Scatterplot distribution between swept area and electricity
generation capacity (in kilowatts) for wind turbines. The line of best
fit has been
included.](Wind-Turbines-Data-Analysis_files/figure-markdown_strict/unnamed-chunk-8-1.png)

There is a positive, very strong, and linear relationship between
turbine swept area and turbine capacity, with a correlation coefficient
of 0.88

## Conclusion

### Findings

The relationships between our outcome variable (electricity generation
capacity) and our predictor variables (hub height, rotor diameter, and
area swept) are all strong, positive, and linear. Moreover, rotor
diameter and swept area both shared a very strong correlation
coefficient of 0.88, while hub height had a strong correlation
coefficient of 0.72. This suggests that hub height, rotor diameter, and
swept area were all correlated to electricity generation capacity. This
can also be viewed as when hub height, rotor diameter, and swept area of
turbines increase, electrical generation capacity of turbines also
increase. Future research in areas related to wind turbines could be in
mechanical and electrical engineering. Mechanical engineers design and
construct the turbine components, like the hub and the rotors, while
electrical engineers design the electrical generation capacity units for
the turbines.

### References

Hoen, B.D., Diffendorfer, J.E., Rand, J.T., Kramer, L.A., Garrity, C.P.,
and Hunt, H.E., 2018, United States Wind Turbine Database (ver. 5.1,
August 2022): U.S. Geological Survey, American Clean Power (ACP)
Association, and Lawrence Berkeley National Laboratory data release
<br><br> 2022 CORGIS Datasets Project. Project by Austin Cory Bart,
Dennis Kafura, Clifford A. Shaffer, Javier Tibau, Luke Gusukuma, Eli
Tilevich. <br><br> More information of the turbine data used can be
found at
<https://www.sciencebase.gov/catalog/item/57bdfd8fe4b03fd6b7df5ff9>
<br><br> The image used can be found at
<https://static.vecteezy.com/system/resources/previews/000/173/679/original/wind-turbine-vector.png>
