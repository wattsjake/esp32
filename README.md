[logo]: /docs/esp32-photo.jpg "ESP32 Microcontroller"
[install]: /docs/screenshot-installation.png "Installation Screenshot"
[add]: /docs/screenshot-add.png "Add ESP32 Plugin Screenshot"
[expand]: /docs/screenshot-expand.png "Expand Window Screenshot"
[next]: /docs/screenshot-next.png "Next Screenshot"
[unsigned]: /docs/screenshot-unsigned.png "Unsigned Screenshot"
[manager]: /docs/screenshot-manager.png "Manager Screenshot"

![alt text][logo]
==================

ESP 32 Microcontroller
---------------------------------------

* Link to: [TODO](TODO.md) 

Link to the ESP32 Getting Started Guide:
--------------
* https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html

Download the ESP32 Toolchain for Ubuntu:
--------------

Followed the instructions from the ESP32 Getting Started Guide:
Link: https://www.beyondlogic.org/getting-started-with-the-espressif-esp-idf-eclipse-ide/#eclipse_ide

1. Download the Eclipse IDE for C/C++ Developers (Linux x86_64)
Link: https://www.eclipse.org/downloads/packages/release/2023-03/r

2. 'cd' into the directory where you downloaded the Eclipse IDE for C/C++ Developers (Linux x86_64) and extract the tar file
Run the following commands in the Terminal:

    ```tar -xzf eclipse-cpp-2020-03-R-linux-gtk-x86_64.tar.gz```

3. Move the eclipse folder to the git32-github folder

4. Add the following to the .gitignore file so that it is not uploaded to github

    ```eclipse/```

    ```workspace/```

5. Use a terminal to open the Eclipse IDE for C/C++ Developers (Linux x86_64)

    ```eclipse/eclipse```

6. Create a new workspace in the eclipse folder additional information here...

    ```/home/jacob/Documents/esp32-git/workspace```

7. Install the ESP32 Toolchain for Ubuntu

    ![alt text][install]

8. Install the ESP32 Eclipse Plugin

    ```Espressif IDF Plugin for Eclipse```

    ```https://dl.espressif.com/dl/idf-eclipse-plugin/updates/latest/```

    ![alt text][add]  

9. Expand the window and select all the options

    ![alt text][expand]

10. Click Next

    ![alt text][next]

11. Click Finish
    You might get a warning about unsigned content. Select the checkbox next to 'unsigned' and click 'Trust Selected'

    ![alt text][unsigned]

12. Restart Eclipse

13. Open the ESP32 Eclipse Plugin

    ![alt text][manager]

Download and Configure ESP-IDF
--------------

1. To use the plug-in, from the help menu, select Download and Configure ESP-IDF to bring up the following dialog box.













