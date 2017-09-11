# Process Control System Experimental Data
This repository contains raw measurement data from the Cybersecurity for Smart Manufacturing Testbed's Process Control System. The testbed is located at the National Institute of Standards and Technology (NIST) in Gaithersburg, Maryland.

## Background
NIST has constructed a testbed to measure the performance impact induced by cybersecurity technologies on Industrial Control Systems (ICS). The testbed allows researchers to emulate real-world industrial manufacturing processes and their control systems by using software simulators and commercial control hardware in the laboratory environment.

<u>Figure 1.</u> View of the Process Control System.![_process_rack]

The focus of this repository is the Process Control System of the testbed. The Process Control System emulates an industrial continuous manufacturing system, a manufacturing process to produce or process materials continuously, where the materials are moving, going through chemical reactions, or undergoing mechanical or thermal treatment continuously. Continuous manufacturing usually implies a 24x7 operation with infrequent maintenance shutdowns and is contrasted with batch manufacturing. Examples of continuous manufacturing systems include chemical production, oil refining, natural gas processing, and waste water treatment.
The Process Control System uses the Tennessee Eastman challenge problem, a real-world industrial chemical manufacturing process, as the simulation model for the chemical reaction. The system integrates the control algorithm developed by Ricker, to control the simulated chemical reaction. With the use of widely deployed industrial hardware like programmable logic controllers (PLCs) and industrial network switches as part of the control loop, this system emulates a complete setup of a continuous chemical manufacturing system \[[NISTIR 8188][_IR8188]\].

__Figure 2.__ Network diagram of the Process Control System.
![_netdiag]

## Measurements
Measurement data are in the raw format obtained directly from the testbed systems. Raw data from an experiment are stored either as an individual file in .xlsx format or a tab inside the combined .xlsx file, depending on the experiment. 

Details about each measurement data file and measurements can be found in the [METADATA][_meta] file.

A detailed description of the Process Control System can be found in the documents [NISTIR 8188, "Key Performance Indicators for Process Control System Cybersecurity Performance Analysis"][_IR8188], and [NISTIR 8089, "ICS Cybersecurity Performance Testbed Design Report"][_IR8089].

## Cybersecurity for Smart Manufacturing Systems Project
Manufacturers are hesitant to adopt common security technologies, such as encryption and device authentication, due to concern for potential negative performance impacts in their systems. This is exacerbated by a threat environment that has changed dramatically with the appearance of advanced persistent attacks specifically targeting industrial systems, such as Stuxnet in 2010, Shamoon in 2012 and BlackEnergy in 2015. Smart manufacturing systems need to be protected from vulnerabilities that may arise as a result of their increased connectivity, use of wireless networks and sensors, and use of widespread information technology. The Cybersecurity for Smart Manufacturing Systems project will deliver a cybersecurity risk management framework with supporting guidelines, methods, metrics and tools to enable manufacturers, technology providers, and solution providers to assess and assure cybersecurity for smart manufacturing systems while addressing the demanding performance, reliability, and safety requirements of these systems. The cybersecurity risk management framework with supporting guidelines, methods, metrics and tools will stimulate manufacturer adoption and enable effective use of security technologies, leading to smart manufacturing systems that offer security, reliability, resiliency and continuity in the face of disruption and major incidents.

More information about the project can be found at [the project landing page][_CSMS].

## License
Data from the robotic system is licensed to the public domain. For more information, please see the [LICENSE][_license] file.

## Disclaimer
Certain commercial entities, equipment, or materials may be identified in this
document in order to describe an experimental procedure or concept adequately.
Such identification is not intended to imply recommendation or endorsement by
the [National Institute of Standards and Technology (NIST)][_NIST], nor is it
intended to imply that the entities, materials, or equipment are necessarily
the best available for the purpose.

[_NIST]: http://www.nist.gov
[_IR8089]: http://nvlpubs.nist.gov/nistpubs/ir/2015/NIST.IR.8089.pdf
[_IR8188]: http://nvlpubs.nist.gov/nistpubs/ir/2017/NIST.IR.8188.pdf
[_CSMS]: https://www.nist.gov/programs-projects/cybersecurity-smart-manufacturing-systems
[_netdiag]: ./readme_assets/te_network.png "Process Control System Network Diagram"
[_meta]: ./METADATA.md
[_process_rack]: ./readme_assets/ProcessControlSystem.jpg "Process Control System"
[_license]: ./LICENSE.md
