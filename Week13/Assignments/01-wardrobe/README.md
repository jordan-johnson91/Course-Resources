# Wardrobe

## Overview

Create a web application for managing the contents of your wardrobe. The app will allow you to add, edit, view, and delete items in your closet.

## Tasks

### Required Tasks

- [ ] Organization of clothing by type
  - [ ] Tops
  - [ ] Bottoms
  - [ ] Shoes
  - [ ] Accessories
- [ ] Outfit Model
- [ ] Controllers
  - [ ] For each model
- [ ] Views
  - [ ] Tops
  - [ ] Bottoms
  - [ ] Shoes
  - [ ] Accessories
  - [ ] Photo properly included where appropriate (index/detail)
  - [ ] /Home/Index.cshtml should be updated for your app

### Stretch Tasks

- [ ] Bootstrap/CSS
  - [ ] Customize the index/detail views to properly show the properties of each item
  - [ ] Updated navbar
  - [ ] Thumbnails
  - [ ] At least 3 other Bootstrap components of your choice
  - [ ] Responsive layout
- [ ] Integrated views with the Outfits model
  - [ ] Show several pieces of clothing from your model on one view

## Details

Design an app that will let you manage the contents of your closet. It should support several different types of clothing stored in your database:

- Tops
- Bottoms
- Shoes
- Accessories

Whether or not you store these as separate tables or a single table is up to you. You will need to have views that allow the user to focus on clothing by type, so keep that in mind when making your decision.

Each item of clothing will need to have the following properties kept with it:
- Name
- Photo
- Type
- Color
- Season
- Occasion

You may add extra properties/columns if you think they are necessary, but keep in mind the MVP!

For the photo, you should use an `nvarchar` column type, and put all photos in the `Content` folder of your project. Save a relative URL of the form `~/Content/myphoto.jpg`, and use that as the `src` of an `<img>` tag in your view file.

You need to determine the appropriate columns/constraints to use for all the other fields.

Your app should support the creation of outfits - a collection of coordinating tops/bottoms/shoes/accessories. Build this into your model, and create views for working with outfits.

A single outfit should consist of zero or one top, zero or one bottom, zero or one pair of shoes, and zero _or more_ accessories. You will need to select an appropriate relationship to properly handle this situation.


### Stretch Tasks

You should customize all of your views to develop the best user experience you can manage. Show photos when appropriate, but don't have them get in the way. Use Bootstrap effectively to make the app responsive for both desktops and mobile devices. Add your own styles to make it a little less "bootstrappy".

Ultimately, your views should be integrated, so you can see all the pictures of each item per outfit.



## Hints

As usual, start with the model, and spend some time considering how many tables to create and how they will be related.

Use the scaffolded controller views to get going and put some data in your app, and then start to work on the index view(s) and making them look nice.

Always target MVP - and once you get there, figure out what the next MVP is!

Use dropdowns when you want to limit a user's possible choices. There's an HTML element that lets you do this!
