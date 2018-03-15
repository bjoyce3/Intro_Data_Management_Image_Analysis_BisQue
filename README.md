# CyVerse Image Management and BisQue Image Analysis

## CyVerse Overview
1. First things first: metadata is as important as data
2. Seriously, metadata
3. Data management is one of the hardest things for phenotyping groups
4. Metadata can be even harder (we'll see some ways to address this)

### User Portal for Sign Up
1. Go to user.cyverse.org
2. Sign In
3. No Account? Sign up for free.
4. The User Portal can be used to access all CyVerse platforms and forms

### Quick Introduction to Phenotyping in CyVerse
1. Slides!
2. These will be the only slides
3. Alright enough slides
4. I'm not here to talk about what we've done; I'm here to talk about what we're going to do

## Moving image data to CyVerse
1. [The Discovery Environment and Data Store][de.cyverse.org]
- Simple Upload with Discovery Environment interface
- Moving lots of data?
  * Zip
  * gzip
  * tar
2. Cyberduck (Windows, Mac)
3. Lots of small files with iCommands (Mac, Linux)
  * Bulk archive the images (zip, gzip,tar)
  * Move the bulk images through Upload, Cyberduck, iCommands
  * Once in archives have moved, unwrap using ibun

## Image Data Handling
1. Data Store
  * Move images into "bisque_data"
  * Images are automatically registered in BisQue
  * Move to CyVerse BisQue
  * Images/Datasets are visible in BisQue
2. Big projects with automatic upload
  * Automated image transfer can be established
  * Contact me (Blake) or request an External Collaborative Partnership (ECP, user.cyverse.org/forms/)

## Metadata in BisQue
1. BisQue can handle 200+ formats of images
2. Many of these formats will import metadata
3. Bulk metadata can be uploaded
  * Use metadata tables (new)

## Simple Image Analysis
### [Setting scale YouTube Documentation](https://www.youtube.com/watch?v=JIn1XNiawVo&t=9s)
1. Go to 'Operations' in the tool bar (next to export)
2. Select 'Calibrate'
3. In the window zoom to the scale in the image
4. Select the line icon
5. Draw a line to determine the scale on a bar within the image
6. Select the number of lengths in the Reference Length widget (1 if only 1 cm, etc)
7. Set pixel resolution to the actual measure (centimeters, ect)
8. Save
9. Select Update Image Metadata
10. The scale bar will be present in the image

### Set lengths in the image
1. In the image (after setting scale) select the line icon
2. Select "Add new semantic type"
3. Enter the name of the length that will show up everywhere
4. Annotate the image
5. Many annotations can be done the same way

### Thresholding and image surface area calculations
Very simple thresholding and surface area calculations can be done on images within BisQue. First, calibrate the image as above (you should see a scale bar on the bottom of the image).
1. Select the 'Operations' button in the tool bar.
2. Select 'Pixel Counter'
3. Select a thresholding value
4. Click the image to select thresholded areas to count surface area/pixels


