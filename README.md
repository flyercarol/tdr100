# TDR100-App
Measurement GUI App for Campbell Scientific TDR100 on Windows and Linux.

TDR100 is a time-domain reflectometry (TDR) step pulse device that send electromagnetic signals to a tranmission line for time-domain travel time and frequency-domain spectrum analysis.

# Download and use
- Made for quick acquisition using Windows 7, 10 and maybe 11.
- No installation required, download this [latest standalone exe](v1.0.1/tdr100_app.exe) and execute it in Windows environment.
	- Or head to [latest build](v1.0.1) and view some released files
- Support in Linux is undergoing

# Why this app?
Campbell Scientific only provided PCTDR software through multiple redirects until the download page. 

Since there are no easy way to better visualize and save data in simple txt format, I thought why not write it up myself.

Referring to their "TDRSDK Software Dev Kit for TDR100" from 2005, I figured out the communication protocols with the TDR100 through RS232, initially developed using python 3.7-3.8.

# Development and testing
Several python libraries are used to complete this TDR100 GUI app：
- matplotlib
- pyserial
- pyinstaller
	- For exe packaging

# How to Cite TDR100-App
I acknowledge the importance of good software to support research, and I note that research becomes more valuable when it is communicated effectively. To demonstrate the value of TDR100-App, I ask that you cite TDR100-App in your work. 
[Quotes above are from Manin(2022)](https://github.com/ManimCommunity/manim)

Currently, the best way to cite TDR100-App is to go to the [repository page and click the "cite this repository" button on the right sidebar](https://github.com/flyercarol/tdr100). This will generate a citation in your preferred format, and will also integrate well with citation managers.

# Future works
- Advanced TDR spectrum analysis based on literatures below
  - Lin, C.-P., **Ngui, Y. J.**, and Lin, C.-H. (2017). A novel TDR signal processing technique for measuring apparent dielectric spectrum. Measurement Science and Technology, 28(1), 015501.
  - Lin, C.-P., **Ngui, Y. J.**, and Lin, C.-H. (2018). Multiple Reflection Analysis of TDR Signal for Complex Dielectric Spectroscopy. IEEE Transactions on Instrumentation and Measurement, 67(11), 2649–2661.
  - **Ngui, Y. J.**, Lin, C.-P., and Wu, T.-J. (2019). Dielectric Spectroscopy Using Dual Reflection Analysis of TDR Signals. Sensors, 19(6), 1299.
  - **Ngui, Y. J.**, and Lin, C.-P. (2022). Self-Referencing TDR Dielectric Spectroscopy Using Reflection-Decoupled Analysis With a Mismatched Section. IEEE Transactions on Instrumentation and Measurement, 71, 1–15.

# Collaborations
Feel free to <a href='mailto:yinjeh.ngui@gmail.com'>drop me an email</a> for any collaboration or comments!


<a href="https://www.buymeacoffee.com/flyercarol" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

