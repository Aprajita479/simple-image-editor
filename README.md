# Image Editor With Download

This is a simple web application that allows users to upload an image, perform various editing operations, preview the edited image, and download the final result. The application utilizes the Cropper.js library for image cropping and manipulation.

## Usage

To use the application, follow these steps:

1. Open the `index.html` file in a web browser.
2. Click on the "Open A Photo" button or drag and drop an image file onto the page.
3. The selected image will be displayed in the editor container.
4. Use the provided options to edit the image:
   - Rotate the image clockwise by clicking the "Rotate Right" button.
   - Rotate the image counterclockwise by clicking the "Rotate Left" button.
   - Flip the image horizontally by clicking the "Flip Horizontal" button.
   - Flip the image vertically by clicking the "Flip Vertical" button.
   - Set the aspect ratio of the image by selecting one of the predefined ratios (16:9, 4:3, 1:1, 2:3) or choose "Free" for a custom ratio.
5. Click the "Preview" button to see a preview of the edited image.
6. Once satisfied with the result, click the "Download" button to save the edited image. The downloaded file will be named as "cropped_[original_filename].png".

## Dependencies

The application relies on the following external resources:

- Google Fonts: Poppins (400, 500)
- Cropper.js (CSS and JavaScript) version 1.5.12

## Files

The application consists of the following files:

- `index.html`: HTML structure of the application.
- `style.css`: CSS styles for the application.
- `script.js`: JavaScript code for handling image editing and download functionality.

## License

This application is licensed under the [MIT License](LICENSE).

## Credits

This application utilizes the following open-source libraries and resources:

- [Cropper.js](https://fengyuanchen.github.io/cropperjs/): A JavaScript image cropper library.
- [Google Fonts](https://fonts.google.com/): Poppins font family.
