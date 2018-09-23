
## Advantages:
* Alert generated can bring driver's attention back to their driving, which will avoid accidents due to driver distractions.
* Government can give incentives to attentive drivers to promote road safety.
* Ride hailing startups can attract more customers by having more number of attentive drivers.

## Business Model:
* Customer Segments: Cab and Bus drivers.
* Unique Value Proposition: No Extra costs other than the costs involved in the Software Development.
* Competitive Advantage: No such robust system currently existing in the market which promotes road safety with such factors.
* Cost Structure: Govt. and startups together can make cost-effective policies (like attentive drivers will get more rides) to give incentives.

## Technology stack:
* Python
* OpenCV
* Keras
* Java
* Android Studio

## Working prototype:
A usual smartphone placed at dashboard (e.g. dashboard of cab drivers) will capture driver’s frames in the background without obstructing current activities of driver (Maps, etc.). These frames will then be passed to a deep learning model classifying his/her driving into safe, moderate or unsafe level of distraction. To ensure frames are not captured unnecessarily while other activities like parking, etc., we have kept a speed threshold of 20 km/h and beyond this, we will start capturing the frames.

Prototype Description:
* Dataset : [State Farm Distracted Driver Detection | Kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection)
* Dataset has multiple categories but we have merged these into 3 categories ,i.e., safe, unsafe and moderate driving. We have resized, grayscaled and also augmented the data (with various rotations,shifts,etc.), so that model will be more fast and  robust(independent of vehicles/drivers). 
* Finally a Convolutional neural network has been used to train the predictive model.

### Accuracy
 <p align="left">
    <img src="pics/accuracy.png" alt="accuracy graphs" width="500"/> 
</p>
