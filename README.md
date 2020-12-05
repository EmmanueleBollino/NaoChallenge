# NAO Planning Challenge
**Group:** You're a big boy, NAO  
**Students:**
 - Agostino Aiezzo, <agostino.aiezzo@studio.unibo.it>
 - Emmanuele Bollino, <emmanuele.bollino@studio.unibo.it>

### Files
Presentation of the project in in the file "Slides.pdf"  
Video demonstration of the dance is in the file "Video"

### Instructions
 - Use the NAO Virtual Machine
 - Make sure that both Python 2 and Python 3 are installed. Default version should be 2
 - Create a PyCharm project and add all the files in here (use PyCharm just to import NaoQi)
 - Import NaoQi from the download (Scaricati) folder, it is already in there
 - Open a terminal in the project path
 - Upgrade pip 3
    ```sh
    /usr/bin/pip3 install --upgrade pip
    ```
 - Install scikit-build
    ```sh
    /usr/bin/pip3 install scikit-build
    ```
 - Install all the requirements
    ```sh
    /usr/bin/pip3 install -r requirements.txt
    ```
 - Change permission for starting script
    ```sh
    chmod 777 ./start.sh
    ```
 - Open Choregraphe in order to simulate NAO
 - Copy the ip and the port of the simulated (or real) NAO
 - Launch the starting script
    ```sh
    ./start.sh
    ```
 - Planning generation may take a while, just be patient
 - Look at NAO!
