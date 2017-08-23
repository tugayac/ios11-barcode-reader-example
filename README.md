# iOS11 Barcode Reader Example
A simple Barcode Reader example, that specifically reads QR Codes. You can generate QR codes pretty much anywhere online. 
I've used [this](http://zxing.appspot.com/generator/) website for my testing.

This example uses the new `Vision` framework being released with iOS 11.

## License
This project uses the MIT license. Please see the license file for details.

## Running on your device
1. Clone this repository.
1. Download XCode 9 Beta (you need to have an Apple developer account for this). (Make sure you have iOS 11 Beta installed one of your Apple devices. I used a 9.7" iPad Pro for testing).
1. Run the application on your iOS 11 device.

## Usage
Simply point the camera at one or more QR codes and little boxes with the content will appear near the detected QR codes, as such:
![qr code app example](https://github.com/tugayac/ios11-barcode-reader-example/blob/master/Example.PNG)

Tapping on the screen will pause the detection and whatever has been detected will remain on the screen. Tapping again will resume detection.

## Author
Arda C. Tugay (ardactugay@gmail.com)
