# Fuel-Economy

The fuel economy of an automobile is the fuel efficiency relationship between the distance traveled and the amount of fuel consumed by the vehicle

Data on Cars used for Testing Fuel Economy
The test data used to determine fuel economy estimates is derived from vehicle testing done at EPA's National Vehicle and Fuel Emissions Laboratory in Ann Arbor, Michigan, and by vehicle manufacturers who submit their own test data to EPA.

Each year, EPA provides fuel economy data to the Department of Energy (DOE), the Department of Transportation (DOT) and the Internal Revenue Service (IRS) so that they can administer their fuel economy-related programs.

DOE publishes fuel economy label values in the annual Fuel Economy Guide.
DOT receives the manufacturers' fleet average fuel economy from EPA, and determines if manufacturers are complying with the federal corporate average fuel economy (CAFE) standards.
EPA provides IRS with the fuel economy data for vehicles which may be subject to the Gas Guzzler tax penalty. IRS is responsible for collecting those taxes from manufacturers.
EPA requires auto manufacturers to change or update their MPG (miles per gallon) values on fuel economy labels (window stickers) if information comes to light that show that the values are too high. See revisions to fuel economy label estimates.

The Problem
Although both datasets are about the same topic—fuel economy—they vary in what is provided.

The 2008 dataset has these columns:

Model
Displ
Cyl
Trans
Drive
Fuel
Sales Area (different name in the 2018 dataset)
Stnd
Underhood ID
Veh Class
Air Pollution Score
FE Calc Appr (not present in the 2018 dataset)
City MPG
Hwy MPG
Cmb MPG
Unadj Cmb MPG (not present in the 2018 dataset)
Greenhouse Gas Score
SmartWay

Whereas the 2018 dataset has these:

Model
Displ
Cyl
Trans
Drive
Fuel
Cert Region (different name in the 2008 dataset)
Stnd
Stnd Description (not present in the 2008 dataset)
Underhood ID
Veh Class
Air Pollution Score
City MPG
Hwy MPG
Cmb MPG
Greenhouse Gas Score
SmartWay
Comb CO2 (not present in the 2008 dataset)
If we tried to combine these datasets without making any changes first, we would run into problems!
