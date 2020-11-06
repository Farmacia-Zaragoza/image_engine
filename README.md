# Image Engine - Main Structure (image_engine)
Image engine available for Brqx Projects
Farmacia Zaragoza 2020-2021
Updated 15-09-2020

Based in Json File or in future rest/graphql entry be able to display images as : 

- One Line List ( Image - Description ) 
- Detailed List
- Gallery / Grid
- Slide ( Partial | Full Screen ) 

+ Have a wizard to instant view type change
+ Enable Zoom effect for images

Example information : 

One Line List Information : Image | Name | Description | Link

Image Behaviour : 

- Simple click --> Zoom
- Double click --> Full Screen Slide

Every object ( image ) will have : 

- Picture ( Resolution based ) 
- Name
- Description
- Link (optional --> Double click)
- Zoom enabled 

Current architecture : 

Platform : Haproxy --> Nginx --> Node Js

Flow     : Node JS Server --> Json File --> React/Angular --> Browser

Future architecture  : 

Platform : Kubernetes managed by RancherOs and Content Delivery


Feel freet to add code information :

+ Main files


+ Codding flow


Related project : 

Client - Javascript - React -->  https://github.com/Farmacia-Zaragoza/image-engine 



