<div align="left">
  <img src="https://github.com/Dalageo/TwinCat3---Elevator/assets/153513781/339d52dc-891d-46d0-b382-10ab86160760" alt="Bechoff TwinCat" width="700"/>
</div>

<div align="left">
  <a href="https://www.beckhoff.com/en-en/products/automation/twincat/" target="_blank">
    <img src="https://img.shields.io/badge/TwinCAT-3.1.4024.55-blue" alt="TwinCAT 3.1.4024.55"></a>
  <a href="https://github.com/Dalageo/TwinCat-VirtualElevator/blob/main/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey" alt="License: CC BY-NC-SA 4.0"></a>
  <img src="https://img.shields.io/github/stars/Dalageo/TwinCat-VirtualElevator?style=social" alt="GitHub stars">
</div>

# Simulating a Three-Floor Elevator System Using TwinCAT PLC Programming

<table>
  <tr>
    <td>
      This repository contains a three-floor elevator control system simulated in the <a href="https://www.beckhoff.com/en-en/products/automation/twincat/">TwinCAT</a> environment as part of a master's course assignment at <a href="https://www.hv.se/en/">University West</a>. The assignment involved the development of the <code>PLCStudent</code>, using PLC programming languages, specifically SFC (Sequential Function Chart) and LD (Ladder Logic) for the elevator functionality, and a ST (Structured Text) function block for the button priority. In this project, <code>PLCSim</code> program, including <code>ElevatorSimulator.TcVIS</code>, was provided by the university. The designed elevator system includes the following functionalities:<br><br>
      - <strong>System Activation</strong>: The control logic and elevator system are activated by pressing the Green Button.<br>
      - <strong>Stop and Resume Operation</strong>: The Red Button stops the elevator movement. Pressing the Green Button again resumes the operation from where it was stopped.<br>
      - <strong>Lamp Usage</strong>: Indicator lamps display the current status of the elevator, such as moving up, moving down, door open, or door closed.<br>
      - <strong>Floor Display</strong>: A digital display inside the elevator shows the current floor number.<br>
      - <strong>Door Control</strong>: Elevator doors automatically close when the elevator is in motion to ensure passenger safety. Upon reaching the destination floor, the doors automatically open, allowing passengers to enter and exit. In addition, a delay is implemented at each floor stop to provide sufficient time for safe exit and entry.<br>
      - <strong>Button Functionality</strong>: Buttons inside the elevator and on each floor call and direct the elevator. The system processes the pressed buttons in the correct order to ensure efficient operation.
    </td>
    <td style="padding-left: 20px;"> 
      <img src="https://github.com/Dalageo/TwinCat3---Elevator/assets/153513781/83b20cbf-1169-4bff-8f58-c547639eb90b" width="2000" style="border-left: 20px solid transparent;">
    </td>
  </tr>
</table>

## Setup Instructions

1. **Download and Install:**
   [TwinCAT 3 download | eXtended Automation Engineering (XAE)](https://www.beckhoff.com/en-en/support/download-finder/search-result/?download_group=97028248&download_item=650023470)
   
2. **Clone the repository:**
   ```sh
   git clone https://github.com/Dalageo/TwinCAT-VirtualElevator.git
   
3. **Navigate to the cloned directory and execute the 'TwinCAT Virtual Elevator.sln' solution file.**

4. **Navigate to TwinCAT directory and execute Start.bat**:
   ```sh
   C:/TwinCAT/3.1/Runtimes/UmRT_Default/Start.bat

5. **Change the Target System in TwinCAT to UmRT_Default.**
   
6. **Activate Configuration.**
   
7. **Login and Start both 'PLCSim' and 'PLCStudent'.**
  
## Contributions

This project was part of a master course assignment at [University West](https://www.hv.se/en/), which provided the initial codebase for <code>PLCSim</code>. Special thanks to the professors at University West who contributed to its development.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). It was chosen to prevent commercial use and to promote free access and open collaboration, ensuring any adaptations remain freely available to everyone.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Citation

```bibtex
@software{Dalageorgos_TwinCAT-VirtualElevator_2024,
author = {Dalageorgos, Konstantinos},
license = {CC-BY-NC-SA-4.0},
month = jun,
title = {{TwinCAT-VirtualElevator}},
url = {https://github.com/Dalageo/TwinCAT-VirtualElevator},
version = {1.0.0},
year = {2024}
}
