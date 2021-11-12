# imporium 

## Description

Easy to use online market place for NFT's of the etherium network. Also a platform for creator to mint their own NFT's


## Data schema example:
```

    Products:
  {
    title: { type: String, required: true },
    creator: { type: String, required: true },
    image: { type: String, required: true },
    description: { type: String, required: true },
    price: { type: Integer, required: true }
  },
  { timestamps: true }
    

    Authentication:
  {
    username: {
      type: String,
      required: true,
    },
    email: { type: String, required: true },
    password_digest: { type: String, required: true, select: false },
  },
  { timestamps: true }
```
![Screen Shot 2021-11-12 at 4 44 10 PM](https://user-images.githubusercontent.com/29825714/141538301-bd8da908-bcad-4459-af2e-ad44126f3fd7.png)

![Screen Shot 2021-11-12 at 4 44 27 PM](https://user-images.githubusercontent.com/29825714/141538327-063a0bbf-778a-4064-a6b2-1a663a4ecf5a.png)

Wireframe UI: https://www.figma.com/file/4zEaux79Sbybg8qrPBSdMx/Imporium?node-id=0%3A1

Component Structure: https://whimsical.com/imporium-RGpNBgc58uN9dbCwspKTjC
## MVP:

- Built using React with at least 6 separate components in an organized and understandable React file structure. 

- Utilizes functional React components.

- Utilizes built-from-scratch API with MongoDB, Mongoose, & Express.js.

- Utilizes React Router for client-side routing.

- Features User Authentication and Profile. 

- Features Home Screen, Listing Screen, & Detail Screen.

- Styled with CSS, utilizing Flex-Box Design.

- Utilizes Two Media Query Screen Sizes for varying viewports.

- Deployed on Netlify, Heroku, & MongoDB Atlas.

## Post MVP

- Implement a user profile page with collections

- Sell button component attached to Product Details

- Three.js animation

- Unique brand logo

## Team Expectations: 

https://docs.google.com/document/d/18g4GcseKsVteMSpRMYecZCKjOtByZ7WB9xaNa0J-ttc/edit

## GitHub Project Board: 

https://github.com/dayi2007/imporium/projects/1?add_cards_query=is%3Aopen

## Time Frames
