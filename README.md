# RazerMS x Apple Pay Integration Documentation

![github-v3](https://user-images.githubusercontent.com/38641542/184131727-07b9c314-b6c3-4ab6-971a-c0ac095b7d8f.jpg)


Apple Pay on the Web
====================
  
### Onboard and use Apple Pay for [Seamless Integration](https://github.com/RazerMS/Integration-RazerMS_JavaScript_Seamless_Integration/blob/master/README.md), [Hosted Integration](https://github.com/RazerMS/Documentation-RazerMS_API_Spec/blob/main/%5Bofficial%20API%5D%20Razer%20API%20Spec%20for%20Merchant%20(v13.37).pdf) and [Direct Server](https://github.com/RazerMS/Documentation-RazerMS_API_Spec/blob/main/%5BOfficial%5D%20Razer%20Direct%20Server%20API%20v1.6.5.pdf)

   1) Create a directory path at your server call .well-known and place the apple-developer-merchantid-domain-association at the following directory.
       - Download the file here [apple-developer-merchantid-domain-association](https://d2x73ruoixi2ei.cloudfront.net/ApplePay/apple-developer-merchantid-domain-association)
   2) Kindly do not alter the filename and follow the following path example : https://www.example.com/.well-known/apple-developer-merchantid-domain-association 
   3) Once the file has be placed at the following path, submit an onboarding request for your merchantID to be enable Apple Pay. 
        -  via RMS merchant portal
            - Navigate to Merchant Profile > Profile Settings > Registered Domain 
            - Select domain 
            - Click onboard
        - Contact our support to help on the onboarding process
   4) Apple will verify the following path in order for us to successfully onboard you as a merchant. 
   5) Upon success onboarding, you can start making payment using Apple Pay with your integration.
   
### Hosted and Seamless Integration
   - There's no integration needed. Only onboarding.

### Direct Server Integration 
   - Refer to Enabling Apple Pay section at [Direct Server](https://github.com/RazerMS/Documentation-RazerMS_API_Spec/blob/main/%5BOfficial%5D%20Razer%20Direct%20Server%20API%20v1.6.5.pdf) documentation 

### Supported platforms
|  | Worldwide (except China) | China | 
| ------------- |:-------------:|:-------------:|
| OS |	iOS 10 and later <br/> macOS 10.12 and later|	iOS 11.2 and later <br>	(Not available in macOS)|


Apple Pay on the App
=========================

### XDK integration

   - [Integrate Apple Pay with Mobile XDK](https://github.com/RazerMS/Documentation-RazerMS_API_Spec/blob/main/RMS%20Mobile%20XDK%20X%20ApplePay.pdf) documentation 
    
   



