# Image Caption
This part of the project contains a 'caption generator'. Its architecture is as follows.

<img src="https://drive.google.com/uc?id=1ja11_VcP4xvSwZGFfLkUnwM6Mi48Qyu5" alt="Broken URL. Contact Anand Menon." width="60%"/>

The underlying VGG16 network trained on ImageNet, is used via 'transfer learning' to help with object classification. The final layer has been replaced, and its features are directly fed into our network. This net can be one of VGG16 or InceptionV3.<br/>
The rest of of the model is custom.