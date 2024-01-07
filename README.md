Execute the Python script in your terminal:

Execute files-
python3 python_file_name

Usage:
The app interface contains:
"Start Monitoring" and "Stop Monitoring" buttons.
An entry field to set the monitoring duration in seconds.
Click "Start Monitoring" to initiate the cursor activity monitoring.

Enter the desired duration in seconds before starting.

Click "Stop Monitoring" to halt the activity monitoring.

Then,
Using PyInstaller:

Run the following command in the terminal:
pyinstaller --onefile python_file_name


Notes:
Ensure to have tkinter and pygame installed. If not, use pip to install them:
pip install tkinter pygame

The default monitoring duration is 10 seconds.

After above commands, the required app will be made in 'dist' directory in present working directory from the corresponding python script.

The app will alert with a sound effect if there's no cursor activity for the specified duration.
