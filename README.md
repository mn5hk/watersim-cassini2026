# WaterSim 🥽
Our submission for the Cassini Space for Water Hackathon. Noordwijk, 2026

## 🌊Description

Globally floods cause damages of around 400 billion USD a year. Similarly, the catastrophe insurance market is currently valued at 215 billion USD and projected to grow to 360 billion USD by 2035. Nonetheless, the tyranny of the changing climate presents a necessary opportunity for technological solutions to protect our businesses and economy, and a profitable business opportunity.

We leverage the European space data and state-of-the-art machine learning technology to predict climate risks such as floods, that affect property valuation and significant business risk. Furthermore, we present novel solutions such as realistic visualization and virtual reality experiences to help asset developers and businesses plan their business ventures and ensure climate risk management. 

## 🛰️Technological Solution

We’ve used the EO4Flood dataset with multiple hydrometeorological datasets such as rainfall, snow, soil moisture, river water height, river width, etc. from European space missions, such as Sentinel 1,2,3,6, SWOT, Jason 1,2,3, etc. However, many of these observations (such as river width, river water level) only cover a few points and are spatiotemporally sparse.

We’ve decided to use machine learning to fill these data gaps. Our innovation lies in the AI models imitating rivers, as we overlay the neurons and the tendons of a neural network onto the river channels and braids - in the form of edges and nodes in a graph, specifically GCN + GRU architecture. This allows us to learn river parameters such as river flow at new locations, using river architecture as a guide.

Furthermore, we have technological solutions for the user experience. More on it in the “Reimagining end user experience” section.

## 🔍Application

For the hackathon, we specifically focus on the property valuation problem, subject to disaster risks such as flood exposure. In the Dresden flood of 2002 in Germany, one of the major companies suffering massive loss was Ikea, as their location got inundated. Thus, such risks are a major concern for businesses and property developers.

## 📈The business case

We target the insurance industry and the finance and mortgaging industry as our clients. Information such as long term property valuation as well as risk exposure of any asset are a huge determinant of profitability of any business venture and any property acquisition.

## 🎨Reimagining end user experience

As a startup aimed at technological innovation and long-term business potential, we look for the best possible experience for our users and their convenience. These include a 3D paranomic view of the asset. This could especially be useful for large property developers on how the landscape development could work.

Furthermore, we present futuristic virtual reality and augmented reality based solutions. The VR technology enables us to experience infrastructure before they are built and before millions of euros or few years are spent to test out a prototype. We use it from the lens of risk management and asset development decision making support tool. 

## 🚀EU Space Technologies

We leverage multiple European space mission data to have a holistic monitoring of the Rhine network. Furthermore, we make use of the European Space Agency project EO4FLOOD (https://eo4flood.org/) to obtain these data in some preprocessed form. 

Satellite technologies used include: GPM for rainfall, Sentinel 2 for snow, SMAP and SMOS for soil moisture, Water Height from the Jason series, Sentinel 3, Sentinel 6 and SWOT, river width from Sentinel 1 and 2, River Discharge from various combination of these products. 

## 🤝Team Formation

🌊Amin Shakya | PhD (ongoing) in Space-borne Hydrology | MSc. Floods | Tech for Good

👩‍🔬Dr. Salima Bahri: Machine Learning Engineer | Nuclear Magnetic Resonance Spectroscopist 

🌍José Miguel Olvera Puentes: Climatologist, Machine Learning & Data Engineering 

🎨Rucha Nagare: UX/UI designer | Human Centered | Problem solver |  Visual strategist

🥽Mohammed Marzouq: Spatial Computing & 3D Data Visualization Engineer | Entrepreneur | Serial Hackathon Winner 

## 📝Key References

EO4Flood Project: https://eo4flood.org/
EO4FLOOD - EO dataset for Hydrology: https://zenodo.org/records/17787732 
Tarpanelli, A., Massari, C., Revilla-Romero, B. et al. The Potential of EO Data for Enhanced Flood Monitoring and Forecasting: A Consortium Assessment. Surv Geophys (2026). https://doi.org/10.1007/s10712-026-09935-w 
Osanlou, K., Getirana, A., Holmes, T., & Cazenave, T. SWOT-based Simulation of River Discharge with Temporal Graph Neural Networks. In NeurIPS 2024 Workshop on Data-driven and Differentiable Simulations, Surrogates, and Solvers. 
