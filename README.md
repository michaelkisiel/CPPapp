# CPPapp
## Sensor error perturbaton application

Measuring the sub-bandage pressure with monitoring devices build on resistive or pneumatic force-sensors seems to be challenging. Studies reveal that theoretically calculated compression pressure according to Laplace Law can not be confirmed with the measured pressures by mentioned monitoring devices [1]. Not much regarded research about changes of the pressure conditions under the bandage when introducing a sensor demonstrate a possible influence by sensor geometries itself [2].

The general explanation is when imagining the sensor as a thin plate first the local curvature is altered and second the change in orientation of the pulling forces in bandage at the edges of the sensor lead to higher pressures between sensor and limb. Vinckx et al. reveal that a correction factor based on their calculated model could ease the problem when comparing experimentally taken measures with theoretical values due to Laplace Law. Further studies gathering the idea of this correction factor show a vague confirmation [3].

This Matlab-App captures the idea of the correction factor for measurements of sub-bandage pressure. It is based on the calculation model defined by Vinckx et al. and extended by some additional equations provided by Khaburi et al.. With the app you can calculate your perturbation factor based on parameters defined by sensor geometries and model/curvature-radius of the limb. Furthermore it shows off a trend line how the perturbation factor would alter according to changes in particular geometry relations.

An additional tab is provided where the pressure applied by bandage can be set. An image is generated to show the pressure distribution in the limb with attached sensor. This is proof of concept and more quality meant interpretation.

![](/cppapp-screenshot1.jpg)
![](/cppapp-screenshot2.jpg)
