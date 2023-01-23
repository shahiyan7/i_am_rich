# i_am_rich

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
## About this project..
In this project we learned how to add asset image in project.

## Steps to add asset image in the project..
1. At the root of your project, create a new folder called Images. You can give any name to this folder such as pictures, graphics, etc.
2.  Add your images inside the Images folder.
3. Provide the image path in pubspec.yamlfile as below.
   * flutter
     * assets: 
     *   - assets/images/lion.png
  
   * ### OR if you have a more than 1 image in image floder use this method:-
     * flutter
     *   assets: <br/>
          - assets/images/
          
4. Display image using the Image.asset() widget.
    *  Image.asset('assets/images/copy url here'),
