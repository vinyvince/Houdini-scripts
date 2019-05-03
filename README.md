# Houdini-scripts
A collection of my personal Houdini Scripts, UI created with PySide2.

### Contact
 [LinkedIn] 
 
 [Vimeo]
 
 [LinkedIn]: https://www.linkedin.com/in/jose-gonzalezvfx/
 [Vimeo]: https://vimeo.com/josezalez
 
## Scripts

* Add parameter comments to camera
* Import multiple agent clips
* Import files
* Principal shader from path



# Add parameter comments to camera

Selecting a camera and a node, gets the node parameters and allows you to select from a list the parameters you want to display on the camera.

Allows to Create, Add and Reset the parameter interface.

With the Add function you can add parameters from different nodes.

The parameters update automatically.


## Usage

Simply add the code to a custom script on your toolbar, save, open it and CTRL+C your camera node, CTRL+V on the camera node box on the plugin to paste the path, do the same for the node you want the parameters from.

![alt tag](https://raw.githubusercontent.com/JoseZalez/Houdini-scripts/master/images_examples/parms_camera_ui.png)
![alt tag](https://raw.githubusercontent.com/JoseZalez/Houdini-scripts/master/images_examples/parms_camera.png)

# Import multiple agent clips

Allows you to import multiple clips to a Agent Clips node selecting them from a list of the path introduced, setting automatically the path and the name.

## Usage

Paste your clip path into the path box and select Import if you want to overwrite older clips or add if you want to keep the older ones.

If your animations are in place simply check the box to set the automatically to In-Place

![alt tag](https://raw.githubusercontent.com/JoseZalez/Houdini-scripts/master/images_examples/import_agent_clip.png)

# Import files

Imports the files in a path or in the subdirectories given a path and an extension.

![alt tag](https://raw.githubusercontent.com/JoseZalez/Houdini-scripts/master/images_examples/import_files_path.png)

# Principal shader from path

Given a path with the textures, creates a principal shader with all the images connected to their respective inputs, returns a message if a image input wast found.

![alt tag](https://raw.githubusercontent.com/JoseZalez/Houdini-scripts/master/images_examples/create_shader.png)


## License

Public domain.
