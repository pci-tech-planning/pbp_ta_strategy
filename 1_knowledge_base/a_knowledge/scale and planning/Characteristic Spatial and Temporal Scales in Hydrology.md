## Literature Review

### 1. Characteristic space scales and timescales in hydrology

#### Understanding Characteristic Scales in Water Resources Management

##### Definition of Characteristic Scales

Characteristic scales in hydrology refer to the specific spatial, temporal, or organizational dimensions at which water resources phenomena exhibit distinct behaviors or patterns. These scales help identify the typical size, duration, or frequency of hydrological processes, such as rainfall, runoff, or groundwater flow. For example, the characteristic scale of a storm event might be a few hours, while the characteristic scale of groundwater flow might span several years and extend across a large catchment area. Understanding these scales is crucial for water resource managers as it allows them to design monitoring networks and predictive models that are appropriately scaled to capture the essential dynamics of these processes.

##### Stationarity and Non-stationarity

Stationarity in hydrology refers to the condition where statistical properties of a process, such as mean and variance, remain constant over time. Non-stationarity, on the other hand, implies that these properties change over time, possibly due to external influences like climate change or land use alterations. For instance, precipitation patterns in a region might be stationary, exhibiting similar average rainfall year after year. Conversely, groundwater levels might be non-stationary if they show a declining trend due to over-extraction. Recognizing whether a process is stationary or non-stationary helps water resource managers choose appropriate models for predicting future conditions and managing resources effectively.

#####  Variograms and Their Fractal Behavior

A variogram is a tool used to describe the spatial correlation of a variable, such as soil moisture or rainfall, over a given area. It plots the variance of the difference between measurements as a function of distance. Fractal behavior in variograms indicates that the spatial variability exhibits self-similarity across different scales, meaning the pattern of variability is similar regardless of the scale of observation. In practical terms, if precipitation shows fractal behavior, small-scale observations can be extrapolated to predict large-scale patterns, aiding in efficient water resource planning and management.

##### Temporal Variograms and E-folding Distances

Temporal variograms extend the concept of variograms into the time dimension, illustrating how the correlation between observations of a variable changes over time. E-folding distance is a specific measure derived from temporal variograms that indicates the time interval over which the correlation between observations decays to 1/e (about 37%) of its initial value. For example, the e-folding distance for daily precipitation might be a day, meaning that observations of rainfall today are highly correlated with tomorrow's rainfall, but this correlation significantly drops after a day. Understanding these temporal patterns is vital for designing short-term weather forecasts and seasonal water management strategies.

##### Aggregation Effects on Spatial Variograms

Aggregation effects occur when measurements taken at finer scales are averaged or summed over larger areas, affecting the observed variability. In spatial variograms, these effects can cause a decrease in variance as the scale of observation increases. For example, point measurements of rainfall might show high variability, but when aggregated over a large watershed, the variability might reduce, reflecting more uniform rainfall patterns. Recognizing aggregation effects helps water managers accurately scale up point observations to regional estimates, ensuring better resource allocation and infrastructure design.

##### Variogram Regularization

Regularization of variograms involves adjusting the variogram to account for the effects of measurement scale and spatial aggregation. This process helps in estimating the variogram for larger, aggregated areas from point measurements. For instance, if water managers have detailed groundwater level measurements at specific points, they can use variogram regularization to predict the groundwater levels across a broader area, improving groundwater management and policy-making. This technique ensures that models and predictions are reliable and applicable at the desired management scale.

### Connecting the Concepts

To manage water resources effectively, it is essential to understand the characteristic scales at which different hydrological processes operate. Recognizing whether these processes are stationary or non-stationary helps in selecting appropriate models for prediction. Variograms provide insights into the spatial variability of hydrological variables, while temporal variograms and e-folding distances offer a temporal perspective. Understanding aggregation effects on spatial variograms is crucial for scaling measurements appropriately. Finally, variogram regularization ensures that point measurements can be extrapolated to larger areas, making predictions and management strategies more reliable. Together, these concepts form a comprehensive framework for understanding and managing the complexities of water resources in a structured and informed manner.


|Title|Author|Year|Core concept/idea|Example|Excerpt|Implications in Water Res. Mgmnt.|
|---|---|---|---|---|---|---|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Characteristic scales in hydrology|Precipitation, runoff, and groundwater levels in Austria|"We analyzed spatial and temporal variograms of precipitation, runoff, and groundwater levels in Austria to examine whether characteristic scales exist and, if so, how big they are."|Understanding characteristic scales helps in designing better monitoring networks and predicting hydrologic responses.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Stationarity and nonstationarity of hydrologic processes|Precipitation and runoff are stationary, groundwater levels are nonstationary|"In time, precipitation and runoff are stationary with characteristic scales on the order of a day and a month, respectively, while groundwater levels are nonstationary."|Identifying stationary and nonstationary processes aids in selecting appropriate models for prediction and management.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Fractal behavior in spatial variograms|Spatial variogram of precipitation is almost fractal|"In space, precipitation is almost fractal, so no characteristic scales exist."|Recognizing fractal behavior in spatial variograms informs the spatial sampling strategies for hydrologic variables.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Temporal variograms and e-folding distances|Temporal variograms of daily precipitation and runoff show characteristic scales of a day and a month|"In time, soil moisture is close to stationary with characteristic scales of the order of 2 weeks while in space soil moisture is nonstationary and close to fractal over the extent sampled."|Knowledge of temporal variograms and e-folding distances improves the temporal resolution needed for monitoring and modeling.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Aggregation effects on spatial variograms|Spatial variogram of catchment precipitation shows aggregation effects|"An analysis of the variograms of catchment precipitation indicates that this break is due to aggregation effects imposed by the catchment area."|Awareness of aggregation effects helps in scaling point measurements to larger areas accurately.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Regularization of variograms|Regularization procedure applied to point variograms to estimate aggregated variograms|"We used a simple procedure proposed by Sivapalan [1986] and used by Western and Blöschl [1999] and others which builds on the probability density functions (pdf) of the distances within the aggregation area to calculate the aggregated variogram."|Regularization of variograms enables better estimations of aggregated hydrologic properties, aiding in regional-scale hydrologic modeling.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Comparison of temporal and spatial variograms|Spatial and temporal variograms compared for various hydrologic variables|"Figure 6b suggests that the regularized variograms provide a reasonable and consistent fit to all three sample variograms."|Comparing temporal and spatial variograms aids in understanding the similarities and differences in space-time behavior of hydrologic variables.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Effect of catchment size on characteristic scales|Runoff response times increase with catchment size|"The temporal variograms for different catchment sizes are almost stationary and the e-folding distances are about two to three weeks."|Understanding the effect of catchment size on characteristic scales helps in predicting hydrologic responses in different-sized catchments.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Spatial aggregation behavior of precipitation and runoff|Comparison of regularized variograms with sample variograms|"The spatial aggregation behavior of precipitation and runoff has been analyzed in more detail by making comparisons with regularized variograms."|Analyzing spatial aggregation behavior assists in improving the accuracy of precipitation and runoff models at different scales.|
|Characteristic space scales and timescales in hydrology|J. O. Skøien, G. Blöschl, A. W. Western|2003|Space-time behavior of characteristic scales|Space-time characteristic scales diagram from Blöschl and Sivapalan (1995)|"The scaling exponents z in T = Lz (where T is time and L is space) are of the order of 0.5 for precipitation, 0.8 for runoff from small catchments, 1.2 for runoff from large catchments, 0.8 for groundwater levels, and 0.5 for soil moisture."|Knowledge of space-time behavior of characteristic scales helps in developing integrated models that consider both spatial and temporal variability.|

### Scale Issues (In hydrology)

#### Understanding Scale in Water Resources Management

##### Scale

In hydrology, scale refers to the spatial or temporal dimension at which hydrological processes and measurements are observed and analyzed. Scale can vary widely, from small-scale processes like soil moisture changes over a few centimeters to large-scale phenomena such as regional precipitation patterns spanning hundreds of kilometers. Understanding the appropriate scale for a given hydrological process is crucial for accurate observation, analysis, and management. For water resource managers, choosing the right scale helps ensure that data collection and modeling efforts are relevant and effective in addressing the specific water-related issues at hand.

##### Upscaling and Downscaling

Upscaling and downscaling are methods used to translate hydrological data and model outputs between different scales. Upscaling involves aggregating detailed, small-scale data to make it applicable at a larger scale, while downscaling translates large-scale data to a finer resolution. For example, upscaling might involve taking detailed soil moisture measurements and using them to estimate average moisture levels for an entire watershed. Downscaling, on the other hand, might involve using regional climate model outputs to predict local weather conditions. These techniques are vital for integrating data across different scales and ensuring that models are accurate and applicable at the desired management level.

##### Extrapolation vs. Scaling

Extrapolation and scaling are two approaches used to apply observations from one context to another. Extrapolation involves extending known data beyond the observed range to predict unknown values, often assuming that existing trends continue. Scaling, however, involves adjusting measurements to account for differences in scale, ensuring that the relationships between variables are preserved across different dimensions. For example, extrapolation might predict future rainfall based on past trends, while scaling adjusts point rainfall measurements to estimate regional averages. Understanding the differences between these approaches helps water managers choose the most appropriate method for their specific needs, ensuring that predictions and estimates are as accurate as possible.

##### Dooge's Classification for Length and Time Scales

Dooge’s classification provides a systematic framework for understanding the different spatial and temporal scales at which hydrological processes operate. The classification helps to categorize processes based on their characteristic length and time scales, guiding the selection of appropriate models and data collection methods.

###### Table 25.1: Dooge’s Classifications for Length and Time Scales in Hydrology

|Class|Length Scale (km)|Time Scale (hours)|
|---|---|---|
|Mega|> 10^3|> 10^4|
|Macro|10^2 - 10^3|10^2 - 10^4|
|Meso|1 - 10^2|1 - 10^2|
|Micro|10^-3 - 1|0.01 - 1|
|Nano|< 10^-3|< 0.01|

This classification helps water resource managers understand which models and data sources are appropriate for different hydrological phenomena, from localized soil moisture measurements (micro scale) to large-scale climate models (macro scale).

##### Longitudinal Dispersivity vs. Overall Displacement Scale

Longitudinal dispersivity is a measure of how a solute spreads along the flow direction in a porous medium, such as groundwater. It indicates the degree to which a contaminant plume spreads out as it moves through the subsurface. The overall displacement scale, on the other hand, refers to the distance over which the solute travels. Understanding the relationship between longitudinal dispersivity and the overall displacement scale is crucial for predicting contaminant transport in groundwater. For example, higher longitudinal dispersivity means that a contaminant plume will spread out more as it travels, potentially affecting a larger area. Water resource managers can use this information to design effective monitoring and remediation strategies for contaminated sites.

### Connecting the Concepts

In water resources management, scale plays a fundamental role in determining the relevance and accuracy of data and models. Upscaling and downscaling techniques allow for the integration of data across different scales, ensuring that small-scale observations can inform large-scale management decisions, and vice versa. Understanding the difference between extrapolation and scaling helps managers choose the right approach for making predictions and estimates. Dooge’s classification provides a framework for selecting appropriate models and data collection methods based on the characteristic scales of hydrological processes. Finally, the relationship between longitudinal dispersivity and overall displacement scale is critical for predicting and managing contaminant transport in groundwater. Together, these concepts provide a comprehensive understanding of how to manage water resources effectively across various scales and contexts.

|Title|Author|Year|Core concept/idea|Example|Excerpt|Implications in Water Res. Mgmnt.|
|---|---|---|---|---|---|---|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Scale, Definition, and Issues|Definitions and examples of scale in hydrology|"One of the many definitions for scale in Webster’s dictionary is a system of grouping or classifying in a series of steps or degrees according to a standard of relative size, amount, importance, perfection, etc."|Clear definitions and understanding of scale help in appropriately addressing and solving scale-related issues in hydrology.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Measurement and Interpretation|Detailed large-scale saturated subsurface interpretation for groundwater flow simulations|"More than 20 years ago Gupta et al. (1984) reported an amazingly detailed large-scale saturated subsurface interpretation for groundwater flow simulations within a multiaquifer system."|Accurate large-scale interpretations enhance groundwater flow simulations and improve groundwater management strategies.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Upscaling and Downscaling|Methods and examples of upscaling and downscaling|"From a generic prospective there are two types of upscaling or downscaling methods: (i) how model equations/parameters change with scale, and (ii) how to best represent variability (space and time) at various scales."|Effective upscaling and downscaling methods ensure the reliability of hydrologic models across different scales.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Alternative Characterizations of Spatial Variability at the Catchment Scale|Characterizing near-surface hydrologic response via simulation in the R-5 catchment|"The 0.1-km2 rangeland catchment (known as R-5) located near Chickasha, Oklahoma has been host to considerable work focused on characterizing near-surface hydrologic response via simulation."|Alternative characterizations improve the understanding and prediction of hydrologic responses at the catchment scale.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Extrapolation from Site to Region|Use of soil taxonomy for upscaling soil properties|"One method of upscaling is extrapolation by means of soil taxonomy. Soil taxonomy (Soil Survey Staff 1999) is a hierarchical classification system that establishes several successive categories of soils."|Extrapolation methods, like soil taxonomy, aid in extending site-specific observations to larger regional contexts.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Querying the Effect of Upscaling|DBCP-contaminated groundwater in the San Joaquin Valley|"Between the late 1950s and the time of its statewide cancellation in August of 1977, there was widespread use of DBCP (1, 2-dibromo-3-chloropropane) throughout California’s San Joaquin Valley."|Querying the effects of upscaling ensures that the implications of scale transitions are considered in water quality management.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Spatial and Temporal Scales in Hydrology|Dooge’s classifications for length and time scales in hydrology|"Dooge’s (1989) classifications for length and time scales in hydrology are given in Table 25.1. Relative to Dooge’s scheme, it is worth pointing out that some scale classifications include a mega class."|Awareness of spatial and temporal scales guides the selection of appropriate models and monitoring strategies.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Hierarchy of Spatial Scales|Organization hierarchy of spatial scales pertinent to non-point source pollution models|"At the surface the focus can be on the land phase, the channel phase, or the combined land and channel phase."|Understanding the hierarchy of spatial scales aids in designing models for non-point source pollution control.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Spatial Variability of Surface, Near Surface, and Subsurface Hydrologic Parameters|Characterization of spatial variability in hydrologic parameters|"The spatial variability of surface, near surface, and subsurface hydrologic parameters is well known (e.g., de Marsily et al., 2005)."|Characterizing spatial variability enhances the prediction accuracy of surface, near-surface, and subsurface hydrologic parameters.|
|Scale Issues|Keith Loague, Dennis L. Corwin|2007|Longitudinal Dispersivity as Dependent on an Overall Displacement Scale|Field longitudinal dispersivity data classified according to reliability|"The dispersivity values shown in Figure 25.5 were estimated from a mixed set of tracer experiments (smaller scales), environmental tracers (larger scales), and numerical simulations."|Reliability of longitudinal dispersivity data supports better prediction and management of contaminant transport in groundwater.|

### Non-linear hydrologic organization

Nonlinear organization in hydrology refers to the complex, non-linear interactions and dependencies among various hydrological processes. Unlike linear systems where changes in input result in proportional changes in output, nonlinear systems exhibit more complex behaviors where small changes can have disproportionately large effects or vice versa. This complexity is seen in many hydrological processes, such as rainfall-runoff relationships, groundwater flow, and river discharge. Understanding the nonlinear organization of these processes is crucial for water resource managers as it affects how predictions and models are developed and used. For example, a small change in rainfall intensity can lead to a significant increase in flood risk in certain watersheds due to nonlinear responses in runoff generation.

##### Hierarchical Organization of Hydrological Processes

Hydrological processes often exhibit hierarchical organization, meaning they are structured in nested levels of processes operating at different scales. For example, at a small scale, soil moisture dynamics influence local infiltration and evaporation, while at a larger scale, these processes aggregate to influence river discharge and regional groundwater recharge. Recognizing this hierarchy is important for integrating data and models across scales. For water managers, this means that interventions at one level (e.g., local soil conservation practices) can have cascading effects on higher-level processes (e.g., watershed hydrology), thus emphasizing the importance of coordinated management across different spatial and temporal scales.

##### Scaling Relationships

Scaling relationships describe how hydrological variables change with scale. These relationships are often expressed using power laws, where one variable changes as a power of another. For example, river discharge might scale with the contributing area, or soil moisture variability might scale with observation scale. Understanding these relationships helps in extrapolating data from small scales to larger ones and vice versa. For instance, knowing that sediment transport scales with river discharge allows managers to predict sediment loads in larger rivers based on measurements from smaller tributaries, thus aiding in river management and sediment control efforts.

##### Optimal Path Exponents

Optimal path exponents describe the efficiency of flow paths in transporting water or solutes through a medium. In hydrology, these exponents can indicate how quickly and efficiently water moves through different pathways in the soil or aquifer. For example, in a highly fractured rock aquifer, the flow paths might be more tortuous, resulting in higher optimal path exponents compared to a more homogeneous sandy aquifer. Understanding these exponents helps water managers design better monitoring networks and predict the movement of water and contaminants through different types of media, ensuring more effective groundwater management.

##### Building Spatio-temporal Scaling Diagrams

Spatio-temporal scaling diagrams are visual tools that summarize the characteristic scales of hydrological processes in both space and time. These diagrams help illustrate how processes like rainfall, runoff, and groundwater flow vary across different spatial and temporal scales. To build these diagrams, one needs to gather data on the characteristic length and time scales of various processes and plot them on a log-log graph. For instance, plotting the spatial extent of different storm events against their duration can help identify patterns and inform the design of monitoring and management strategies that are appropriately scaled. These diagrams are useful for water managers to visualize and understand the interactions between different processes and scales, aiding in more comprehensive resource planning.

##### Fundamental Network Length

The fundamental network length refers to the characteristic scale at which a network, such as a river or groundwater flow network, organizes itself. It represents the basic building block of the network structure. For example, in a river network, the fundamental length might be the average length of first-order streams, which then combine to form higher-order streams. Understanding this fundamental length helps in predicting how the network will respond to changes, such as increased runoff or changes in land use. For water resource managers, this concept is crucial in designing effective monitoring networks and predicting the impacts of management actions on the larger hydrological network.

##### Non-linear Scaling of Hydrological Processes

Non-linear scaling refers to the way hydrological processes scale with changes in size, time, or other factors in a non-linear manner. This means that doubling the size of a watershed, for example, does not necessarily double the runoff. Instead, the relationship might follow a power law or other non-linear functions. Recognizing these non-linear scaling behaviors is important for accurate modeling and prediction. For example, when scaling up results from small experimental plots to whole watersheds, managers need to account for these non-linearities to avoid over- or under-estimating water yields, sediment transport, or nutrient loads.

##### Hierarchical Organization and Growth of Flow Paths for Surface, Subsurface, and Hyporheic Zone

Flow paths in hydrological systems, including surface streams, subsurface groundwater flow, and the hyporheic zone (where surface water and groundwater mix), often exhibit hierarchical organization and growth. At the surface, small tributaries join to form larger streams, which eventually contribute to major rivers. In the subsurface, water moves through a network of pores, fractures, and conduits, forming a hierarchical structure of flow paths. The hyporheic zone, situated between the surface and subsurface, plays a critical role in nutrient cycling and habitat provision.

Understanding this hierarchical organization and growth of flow paths is crucial for managing water resources effectively. For example, surface water management needs to consider how changes in small tributaries can impact larger river systems. Groundwater management requires an understanding of how flow paths through different geological layers interact. The hyporheic zone's role in nutrient cycling means that protecting these areas can improve water quality downstream. For water managers, this hierarchical perspective ensures that interventions are designed with a holistic understanding of the interconnected nature of hydrological systems.

### Connecting the Concepts

In water resources management, recognizing the nonlinear and hierarchical organization of hydrological processes is essential for developing effective strategies and interventions. Scaling relationships and optimal path exponents provide insights into how these processes behave across different scales and media, guiding the development of accurate models and predictions. Building spatio-temporal scaling diagrams helps visualize the interactions between processes and scales, facilitating better planning and decision-making. Understanding the fundamental network length aids in designing monitoring networks that capture the essential dynamics of hydrological systems. Non-linear scaling behaviors must be accounted for to avoid errors in scaling up or down. Lastly, the hierarchical growth of flow paths across surface, subsurface, and hyporheic zones underscores the need for integrated management approaches that consider the interconnected nature of these systems. Together, these concepts form a comprehensive framework for managing water resources in a complex, interconnected environment.

|Title|Author|Year|Core concept/idea|Example|Excerpt|Implications in Water Res. Mgmnt.|
|---|---|---|---|---|---|---|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal scaling of hydrologic processes|Soil depth, vegetation root lateral spread, drainage basin length|"We revisit three variants of the well-known Stommel diagrams that have been used to summarize knowledge of characteristic scales in time and space of some important hydrologic phenomena and modified these diagrams focusing on spatiotemporal scaling analyses of the underlying hydrologic processes."|Spatiotemporal scaling helps in predicting hydrologic processes across different scales, improving water resource management.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Hierarchical organization of optimal subsurface flow paths|Root lateral spread of vegetation, drainage basin organization|"The principle of a hierarchical organization of optimal subsurface flow paths could underlie both root lateral spread (RLS) of vegetation and drainage basin organization."|Understanding hierarchical organization aids in optimizing subsurface flow path design and management.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal scaling relationships|Soil formation, vegetation growth|"We use existing scaling relationships for vegetation growth and soil formation, both of which refer to the same fundamental length and timescales defining flow rates at the pore scale but different powers of the power law relating time and space."|Scaling relationships inform the development of models that account for variability in hydrologic processes.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Scaling of chemical weathering|Soil depth dependence on downward water flux|"Chemical weathering, which is typically limited by downward water flux (infiltration) in the unsaturated zone, is the principle limiting factor of soil development."|Insights into chemical weathering assist in soil and water conservation practices.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Optimal path exponent in 2D and 3D|Vegetation growth, soil development|"The power s was chosen, for soil development, as the inverse of the percolation backbone dimensionality, 1/Db = 0.53, and, for vegetation growth, equal to the inverse of the 2D percolation optimal path exponent, 1/Dopt = 0.83."|Knowledge of optimal path exponents enhances predictions related to vegetation growth and soil development.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal scaling diagrams|Surface vs. subsurface hydrologic processes|"We consider a few basic concepts presented in such figures in the light of recent work on the spatial scaling of river networks, the spatiotemporal scaling of chemical weathering, soil formation, and vegetation growth."|Spatiotemporal scaling diagrams provide a framework for integrating surface and subsurface hydrologic processes in models.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Fundamental network length scale|Soil depth, vegetation root lateral spread|"In each case, the fundamental network length scale is on the order of a particle (or plant xylem) size."|Identifying fundamental network length scales helps in optimizing the design of monitoring networks.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Hierarchical growth of flow paths|River networks, root lateral spread|"The development of river networks and root lateral spread (RLS) of vegetation can be described by the hierarchical growth of flow paths."|Understanding hierarchical growth aids in managing river networks and vegetation spread effectively.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Non-linear scaling of hydrologic processes|Vegetation growth, soil formation|"Non-linear scaling of hydrologic processes is reflected in the relationships for soil formation and vegetation growth."|Non-linear scaling insights improve the accuracy of models predicting soil formation and vegetation growth.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal variability of hydrologic processes|Soil formation, river drainage development|"Our proposed power-law length–time scaling relationship can be represented in the following form: x = x0 (t / t0)^s."|Spatiotemporal variability knowledge enhances the management and conservation of water resources at different scales.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal scaling of hydrologic processes|Soil depth, vegetation root lateral spread, drainage basin length|"We revisit three variants of the well-known Stommel diagrams that have been used to summarize knowledge of characteristic scales in time and space of some important hydrologic phenomena and modified these diagrams focusing on spatiotemporal scaling analyses of the underlying hydrologic processes."|Spatiotemporal scaling helps in predicting hydrologic processes across different scales, improving water resource management.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Hierarchical organization of optimal subsurface flow paths|Root lateral spread of vegetation, drainage basin organization|"The principle of a hierarchical organization of optimal subsurface flow paths could underlie both root lateral spread (RLS) of vegetation and drainage basin organization."|Understanding hierarchical organization aids in optimizing subsurface flow path design and management.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal scaling relationships|Soil formation, vegetation growth|"We use existing scaling relationships for vegetation growth and soil formation, both of which refer to the same fundamental length and timescales defining flow rates at the pore scale but different powers of the power law relating time and space."|Scaling relationships inform the development of models that account for variability in hydrologic processes.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Scaling of chemical weathering|Soil depth dependence on downward water flux|"Chemical weathering, which is typically limited by downward water flux (infiltration) in the unsaturated zone, is the principle limiting factor of soil development."|Insights into chemical weathering assist in soil and water conservation practices.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Optimal path exponent in 2D and 3D|Vegetation growth, soil development|"The power s was chosen, for soil development, as the inverse of the percolation backbone dimensionality, 1/Db = 0.53, and, for vegetation growth, equal to the inverse of the 2D percolation optimal path exponent, 1/Dopt = 0.83."|Knowledge of optimal path exponents enhances predictions related to vegetation growth and soil development.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Spatiotemporal scaling diagrams|Surface vs. subsurface hydrologic processes|"We consider a few basic concepts presented in such figures in the light of recent work on the spatial scaling of river networks, the spatiotemporal scaling of chemical weathering, soil formation, and vegetation growth."|Spatiotemporal scaling diagrams provide a framework for integrating surface and subsurface hydrologic processes in models.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Fundamental network length scale|Soil depth, vegetation root lateral spread|"In each case, the fundamental network length scale is on the order of a particle (or plant xylem) size."|Identifying fundamental network length scales helps in optimizing the design of monitoring networks.|
|Non-linear hydrologic organization|Allen Hunt, Boris Faybishenko, Behzad Ghanbarian|2021|Hierarchical growth of flow paths|River networks, root lateral spread|"The development of river networks and root lateral spread (RLS) of vegetation can be described by the hierarchical growth of flow paths."|Understanding hierarchical growth aids in managing river networks and vegetation spread effectively.|

### Overall Synthesis
In water resources management, understanding the characteristic spatial and temporal scales of hydrological processes is essential for effective monitoring, modeling, and decision-making. This synthesis aims to integrate spatial and temporal scales, identifying relevant hydrological processes, special considerations, and their management implications. The tables provided below serve as a comprehensive reference for water resource managers, helping them understand and apply these concepts in practical scenarios.

### Methodology

#### Identifying Realistic vs. Unrealistic Matches

To ensure that the hydrological processes listed in each cell of the tables are realistic and appropriate for the given spatial and temporal scales, we used the following criteria:

1. **Spatial Scale Relevance**: Hydrological processes must be observable or manageable at the given spatial scale. For example, soil moisture dynamics are relevant at small scales (nano to micro), while regional precipitation patterns are observed at larger scales (macro).
    
2. **Temporal Scale Relevance**: The temporal scale must match the duration over which the hydrological process occurs. Instantaneous events like rainfall intensity are relevant at very short temporal scales (nano), while long-term processes like climate trends require longer temporal scales (mega).
    
3. **Process Scale Compatibility**: Hydrological processes are matched with spatial and temporal scale combinations where they naturally occur. For instance, river discharge is typically observed at meso spatial scales and meso to macro temporal scales, while groundwater recharge is relevant at meso to macro spatial scales and meso to macro temporal scales.
    
4. **Avoiding Unrealistic Combinations**: Processes that do not realistically occur at certain scale combinations are excluded or marked as not applicable (N/A). For example, it is unrealistic to study long-term climate trends at nano spatial scales, so such combinations are excluded.
    

#### Steps to Create the Tables

1. **Spatial and Temporal Scales**: We first identified characteristic spatial and temporal scales using Dooge’s classification model as a starting point. Spatial scales are measured in kilometers (km), and temporal scales are measured in days.
    
2. **Assigning Hydrological Processes**: Relevant hydrological processes were then matched to appropriate scale combinations based on the criteria outlined above.
    
3. **Adding Special Considerations and Management Implications**: For each realistic scale combination, special considerations and management implications were derived from the core concepts discussed in the provided papers and this conversation.
    

### Tables

#### Table 1: Relevant Hydrological Processes

|Spatial \ Temporal|< 0.01 days (Nano)|0.01 - 1 day (Micro)|1 - 100 days (Meso)|100 - 1000 days (Macro)|> 1000 days (Mega)|
|---|---|---|---|---|---|
|< 0.001 km (Nano)|Instantaneous rainfall intensity|Rapid soil moisture changes|N/A|N/A|N/A|
|0.001 - 1 km (Micro)|N/A|Daily evaporation rates|Flood events|N/A|N/A|
|1 - 100 km (Meso)|N/A|N/A|River discharge, Seasonal soil moisture variations|Seasonal flow patterns|N/A|
|100 - 1000 km (Macro)|N/A|N/A|N/A|Regional precipitation patterns|Long-term climate trends|
|> 1000 km (Mega)|N/A|N/A|N/A|N/A|Global hydrological cycle|

#### Table 2: Special Considerations

|Spatial \ Temporal|< 0.01 days (Nano)|0.01 - 1 day (Micro)|1 - 100 days (Meso)|100 - 1000 days (Macro)|> 1000 days (Mega)|
|---|---|---|---|---|---|
|< 0.001 km (Nano)|Nonlinear responses, fractal behavior|Nonlinear responses, fractal behavior|N/A|N/A|N/A|
|0.001 - 1 km (Micro)|N/A|Temporal variograms, e-folding distances|Stationarity and non-stationarity|N/A|N/A|
|1 - 100 km (Meso)|N/A|N/A|Aggregation effects, variogram regularization|Temporal aggregation effects, spatio-temporal scaling|N/A|
|100 - 1000 km (Macro)|N/A|N/A|N/A|Spatial variograms, scaling relationships|Non-linear scaling, hierarchical growth of flow paths|
|> 1000 km (Mega)|N/A|N/A|N/A|N/A|Hierarchical organization, scaling diagrams|

#### Table 3: Water Resources Management Implications

|Spatial \ Temporal|< 0.01 days (Nano)|0.01 - 1 day (Micro)|1 - 100 days (Meso)|100 - 1000 days (Macro)|> 1000 days (Mega)|
|---|---|---|---|---|---|
|< 0.001 km (Nano)|Flash flood warning systems and real-time monitoring|Real-time soil moisture monitoring for precision agriculture|N/A|N/A|N/A|
|0.001 - 1 km (Micro)|N/A|Daily irrigation scheduling|Implementing seasonal flood preparedness measures|N/A|N/A|
|1 - 100 km (Meso)|N/A|N/A|Watershed management and regional water supply planning|Long-term water supply planning and drought management strategies|N/A|
|100 - 1000 km (Macro)|N/A|N/A|N/A|Regional climate adaptation and large-scale water infrastructure projects|Strategic planning for climate resilience and sustainable water resource management|
|> 1000 km (Mega)|N/A|N/A|N/A|N/A|Developing global water resource management policies and agreements|

### Takeaway Messages on the Role of Characteristic Scales 

1. **Importance of Understanding Characteristic Scales**: Recognizing the specific spatial and temporal scales at which hydrological processes operate is essential for effective water resources management. It helps in designing appropriate monitoring systems and predictive models.
    
2. **Stationarity vs. Non-stationarity**: Identifying whether a hydrological process is stationary or non-stationary aids in selecting the right models for prediction and management. For instance, stationary processes like daily precipitation patterns can be modeled differently than non-stationary processes like groundwater levels.
    
3. **Role of Variograms**: Variograms are crucial tools for understanding the spatial correlation of hydrological variables. They help in determining the scale at which data should be collected and analyzed, ensuring that models accurately reflect real-world conditions.
    
4. **Temporal Variograms and E-folding Distances**: Temporal variograms and e-folding distances provide insights into the time scales over which hydrological variables are correlated. This information is vital for planning short-term weather forecasts and seasonal water management strategies.
    
5. **Aggregation Effects**: Understanding how spatial and temporal aggregation affects hydrological data ensures that point measurements can be accurately scaled up to larger areas. This is critical for regional water resource planning and management.
    
6. **Variogram Regularization**: Regularizing variograms helps estimate hydrological properties over aggregated areas from point measurements. This technique improves the reliability of regional-scale hydrological models.
    
7. **Scaling Relationships**: Scaling relationships describe how hydrological variables change with scale. These relationships help in extrapolating data from small scales to larger ones and vice versa, which is crucial for integrated water resource management.
    
8. **Hierarchical Organization**: Hydrological processes often exhibit hierarchical organization, with nested levels of processes operating at different scales. Recognizing this hierarchy is important for coordinating management efforts across different spatial and temporal scales.
    
9. **Non-linear Scaling**: Non-linear scaling behaviors must be accounted for to avoid errors in scaling up or down. Understanding these behaviors improves the accuracy of models predicting water yields, sediment transport, and nutrient loads.
    
10. **Spatio-temporal Integration**: Combining spatial and temporal scales in hydrological studies helps visualize and understand the interactions between different processes and scales. This integration is essential for comprehensive water resources planning, monitoring, and management.


### 10  Takeaway Messages on the Role of Characteristic Scales in Water Resources Management

1. **Designing Effective Monitoring Networks**: Understanding characteristic spatial and temporal scales helps in designing monitoring networks that capture relevant hydrological data at appropriate scales, improving data accuracy and reliability.
    
2. **Selecting Appropriate Models**: Identifying whether hydrological processes are stationary or non-stationary guides the selection of suitable models for predicting water resources behavior, ensuring more accurate forecasts.
    
3. **Optimizing Irrigation and Soil Management**: Recognizing small-scale processes like soil moisture dynamics and evaporation rates aids in optimizing irrigation schedules and soil management practices, enhancing water use efficiency.
    
4. **Enhancing Flood Management**: Knowledge of relevant scales for processes such as instantaneous rainfall intensity and flood events enables better design of flood warning systems and preparedness measures, reducing flood risk.
    
5. **Improving Watershed Management**: Aggregation effects and variogram regularization help in scaling up point measurements to watershed levels, supporting effective watershed management and regional water supply planning.
    
6. **Informing Climate Adaptation Strategies**: Understanding regional precipitation patterns and long-term climate trends at macro and mega scales informs climate adaptation strategies, ensuring sustainable water resource management under changing climatic conditions.
    
7. **Integrating Surface and Groundwater Management**: Recognizing the hierarchical organization of surface and subsurface hydrological processes supports integrated management approaches, ensuring coordinated surface and groundwater management.
    
8. **Planning for Seasonal Variability**: Temporal variograms and knowledge of e-folding distances aid in planning for seasonal variations in hydrological processes, such as river discharge and groundwater recharge, enhancing water supply reliability.
    
9. **Developing Sustainable Groundwater Policies**: Understanding long-term groundwater recharge cycles and depletion trends at meso to mega scales supports the development of sustainable groundwater extraction policies and long-term water resource planning.
    
10. **Addressing Sediment and Contaminant Transport**: Knowledge of scaling relationships and longitudinal dispersivity informs the management of sediment transport and contaminant movement in water bodies, aiding in the design of effective remediation and maintenance programs.
