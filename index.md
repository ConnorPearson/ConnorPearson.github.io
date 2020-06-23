## Welcome to Connor's Development profile

This is the central hub for all my published work. Some of it is still under development, and some post development. 

### Projects

My ongoing / complete projects are shown below. This section will provide a brief overview of what the projects main goals are and their features.

# 1. convolutional-neural-network
## Brief
The program was started as an intention to help develop my understanding of image processing as well as the inner functions of a neural network. After a long run of development the project was sidelined after I started studying but has now re entered development as a side project.

## Development intentions
The project is going to be developed in two parts :

### Image processing
The image processing code, which will prepare the image data for entry into the neural network. This code will process the image data into a single line of data that can be entered into the neural networks input nodes. 

### Neural Network
The second part of the project will be a neural network that will be developed independently from the image processing code. The neural network will be added to the image processing code upon completion.

# 2. contact-tracing-app
## Brief
This project was created for a competition. The task was to create a form of solution to contact tracing for the currently ongoing corona virus pandemic.

## Development intentions
The project was specifically chosen to increase my understanding of Android app development. Therefore the project was created in Android Studio with Java (instead of Kotlin).

## Bluetooth functionality
One of the most difficult parts of the project was finding the appropriate Bluetooth API for the use case. Since this was also my first time using any form of Bluetooth project I had to educate myself on a lot of the APIs abilities. After trying basic Bluetooth pairing, and also Bluetooth Beacons I discovered BLE. BLE is Bluetooth Low Energy and is used on smart watched and some Bluetooth speakers.

Using BLE allowed the app to connect without needing to pair, which would introduce a lot of security vulnerabilities and of course require people in proximity to pair once in contact which is way more comedic than functional really. Beacons were a promising technology however they are not supported on a lot of devices. 

While BLE was considered I was expecting it to be the same as basic Bluetooth but with restrictions. However, it has many functions that Bluetooth alone does not. An it was the use of a BLE Advert and a BLE Scan that allowed the app to work. There is more extensive descriptions of the Bluetootha implementation on the projects repo inside the PDF documentation file.


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Phoenix-Alpha/Phoenix-Alpha.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
