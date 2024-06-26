# watch_run Project

watch_run is designed specifically for Python developers. It abandons the intensive use of print statements, logging, and debuggers, significantly reducing manual effort.
## Key Advantages:

One-Click Debugging: No need to embed print statements or debug code. Simply start the tool to enter a highly optimized debugging environment, keeping your code clean and pure.

Locating Intermittent Defects: For bugs that are hard to reproduce, set up monitoring easily, greatly shortening the diagnosis cycle.

Multi-Target Monitoring: Easily set up watch lists to monitor numerous variables and function call traces, which is especially important for understanding complex logic and performance bottlenecks.

Performance Overhead: Carefully optimized algorithms maintain near-native execution speed in deep debugging mode, overcoming the performance bottlenecks of traditional debugging.

In summary, watch_run is a significant leap in Python debugging tools. With its outstanding usability and extreme performance optimization, it greatly widens the efficiency gap, paving a highly efficient programming path for Python that other languages do not possess.

## Supported Platforms Now

- **Operating Systems**
  - macOS
  - Windows

- **Python Versions**
  - Python 3.7
  - Python 3.8
  - Python 3.9
  - Python 3.10
  - Python 3.11
  - Python 3.12


## Installation

```sh
pip install watch_run
```

## Usage

```sh
watch_run main.py
```
Run 'watch_run main.py' in the same place where you previously run 'python3 main.py'. This is the only command.


Tkinter is needed.
Running the 'watch_run main.py' command will launch a simple user interface.

## Button Panel on User Interface

Run

    Start running the program. During execution, settrace will be automatically started, and the previous terminal will be bound for printing.
    If you are on a Mac system, you can use 'watch_run main.py &' to continue allowing the terminal to execute new commands.

Toggle Simple/Fast Mode

    Toggle Simple/Fast Mode
Add Class

    Click this button to add a new class entry. The new entry will include input fields for class name, variable names, list names, and instance names.
    Each entry can only have one class name, while variable names, list names, and instance names can be multiple, separated by commas.
    If you want to track regular variables instead of class objects, you don't need to fill in the class name.
    Instance names refer to the variable names used when creating class instances, used for filtering. For example, aaa = classA() and bbb = classA(), if you enter aaa in the instance name field, bbb will not be monitored.


Add Stop Line

    Click this button and select the Python file path and enter one or more line numbers (separated by commas), then click enable.
    When the thread executes to this line, it will stop settrace and resume normal running speed, no longer monitoring regular variables, but still monitoring class objects. This monitoring does not affect the running speed.

Save Data

    Click this button to save the current configuration data. Usually, you don't need it because the data is automatically saved when you click the Run button.

Open History to Edit

    Click this button to open and edit the history record file of the monitoring targets.

Show Trace Result (time sequence)

    Click this button to display monitoring results, including value changes and the call stack. This is the raw log file sorted by record time, and it is automatically cleared each time the program runs.

Show Trace Result (instances sequence)

    Click this button to read the raw log file and organize the information for each monitored object. The monitoring results are displayed in an instance-sorted manner to better showcase each monitored object.

Print in Terminal (instances sequence)

    Click this button to print the instance-sorted monitoring results in the terminal.

Clear Info Before

    Click this button to clear the monitoring information recorded during this run, but keep the list of monitored objects so that subsequent monitoring information is highlighted.

Buy Verification Serial

    Click this button to see the computer encrypted serial.
    Provide this encrypted serial to purchase a verification serial. Each verification serial can only be used on a specific computer.

Attention

    Click this button to view notes and usage tips.

## Features

Monitor Ordinary Variables: Free of charge. Provides monitoring at 10-15 times the normal runtime speed.

Monitor through Class Objects: Paid feature. Enables monitoring in a production environment without impacting performance.
You can purchase this feature through the application interface.

## License

This project uses the following third-party libraries:
Cryptography library (https://cryptography.io/) which is licensed under the Apache License 2.0.(Include the full text of the Apache License 2.0 here)



