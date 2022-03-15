
# BioInv_Project
BioInv is an inventory tracking system for biological samples. Users will have the ability to add, update, or delete samples their samples.
#### Full-Stack CRUD App created during GA SEI program (Project 2)

## Tech Stack
- HTML
- CSS/Bootstrap
- Javascript
- Node.js
- Express.js
- Mongoose/MongoDB

## API
- [Abstract Email Verification API](https://www.abstractapi.com/email-verification-validation-api?ref=devresourc.es)
- This API will verify a user's email 

## Application Breakdown
- a user will have the capability to login to their sample managment system that is specific to their organization/laboratory
- the user will have the capability to add their samples to boxes which are stored in a temperature regulated freezer (storage)
- the boxes are a 4x4 storage compartment that will house the sample vials

## MVP Goal:
- Build an sample inventory tracking system that allows users from an orgnization to manage laboratory samples
- An authorized user will have the capability to add, edit, and remove samples
- Prevents users from delete others samples or containers if not authorized
- Have one storage location that will house all sample boxes



## ERD
https://miro.com/app/board/uXjVOF93Xdg=/?invite_link_id=681946647112

![BioInv ERD](https://user-images.githubusercontent.com/43145834/158291669-62a7005a-a5c6-4fd0-9c85-f0434bb09b52.png)

## Wireframes 
![BioInv Wireframe](https://user-images.githubusercontent.com/43145834/158244343-9340251c-e34e-4592-b4cd-acfe13b43ac2.png)





## Stretch goals
- create a log section
- have a note section for the edited/deleted samples to log a message for reason for modifying sample (commented log section)
- The application will have the capability to have multiple storage locations (freezers, ambient, cold room)
- create multiple box grids (3x3,10x10,etc.)
- add a feature to upload/save experiments and have them linked to samples
