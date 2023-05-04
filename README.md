### How to Construct The Datasets
The dataset is just the basic data of slice requests dataset. It describes the resource demand of slice instances from several vertical industries, including remote driving, intelligent transport system, low voltage collection of smart grid, V2I-driver information service and so on. When we perform experiments, network slice instances are randomly selected, and its number follows the possion distribution. More details about the properties of the dataset have been illustrated below.

- The `Service Type` indicates what kind of services provided by 5G network slices.
- The `Slice Type` only contains one of three typical network slice Type, which is URLLC, mMTC and eMBB.
- the property of `Time`, ranging form 1 to 23, represents how long the networks instances serving for mobile network tenants and its unit is hour.
- The other properties the resources of network slice requests, including two kind of computing resources and the bandwith of uplink and downlink.





