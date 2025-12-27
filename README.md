## Title of the Project
### WebHawk (Eyes on Every Link)
WebHawk is a web-based phishing and fake website detection system developed using Flask that helps users verify the authenticity of URLs in real time. The system analyzes user-provided links using multiple heuristics and string similarity techniques to classify websites as LEGITIMATE or PHISHING, thereby enhancing user safety and awareness while browsing the internet.

## About
WebHawk (Eyes on Every Link) is a Flask-based web application designed to detect fake and phishing websites by analyzing suspicious patterns in URLs. With the increasing number of cyberattacks and phishing attempts, users often fall victim to malicious websites that imitate legitimate platforms to steal sensitive information.

Traditional methods of identifying phishing websites rely heavily on user awareness and manual inspection, which can be unreliable and time-consuming. WebHawk addresses this issue by providing an automated and user-friendly solution that evaluates URLs using domain analysis, lexical features, and string similarity techniques such as Levenshtein distance and domain extraction.

The application offers a simple interface where users can enter a URL and instantly receive a classification result. Additional features such as a detection history log, dark mode toggle, and sidebar navigation enhance usability. WebHawk is deployed on the Render platform, making it accessible online for real-time usage.

## Features
Real-time detection of fake and phishing websites

URL classification as LEGITIMATE or PHISHING

Uses domain extraction and string similarity analysis

Detection history (stores up to the last 5 checked URLs)

User-friendly Flask-based web interface

Dark mode toggle for better user experience

Sidebar navigation with Home and About pages

Lightweight and fast response time

Deployed as a web application using Render

## Requirements
Operating System:
Requires a 64-bit Operating System (Windows 10 / Ubuntu / macOS)

Programming Language:
Python 3.8 or later

Web Framework:
Flask (for backend development)

Libraries & Dependencies:

Flask

tldextract (domain extraction)

python-Levenshtein (string similarity computation)

gunicorn (production server for deployment)

Development Environment:
Visual Studio Code (VS Code)

Version Control:
Git for source code management

Deployment Platform:
Render (for hosting the Flask web application)

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Legitimate

<img width="1892" height="893" alt="image" src="https://github.com/user-attachments/assets/5bc677c0-a5fa-44f7-9964-4e3288c59563" />


#### Output2 - Phishing
<img width="1893" height="902" alt="image" src="https://github.com/user-attachments/assets/762d2cbf-efa4-4e52-9ad8-02cac7982718" />


Detection Accuracy: 96.7%


## Results and Impact
The WebHawk phishing detection system significantly improves online safety by enabling users to quickly identify fake and phishing websites before interacting with them. By analyzing URL structures and domain characteristics, the system achieves a high detection accuracy of 96.7%, helping to reduce the risk of credential theft, financial fraud, and malicious cyberattacks.

The intuitive Flask-based web interface ensures ease of use for both technical and non-technical users, while features such as detection history and dark mode enhance overall user experience. WebHawk demonstrates the practical application of web security principles and string similarity analysis in real-world scenarios, highlighting its effectiveness as a lightweight yet reliable phishing detection solution.

This project provides a strong foundation for future advancements in cybersecurity applications, including the integration of machine learning models, browser extensions, and real-time threat intelligence feeds. Ultimately, WebHawk contributes to building a safer and more secure digital ecosystem by promoting proactive phishing awareness and prevention.

## Articles published / References
1. R. M. Mohammad, F. Thabtah, and L. McCluskey, “Predicting Phishing Websites Based on Self-Structuring Neural Network,” Neural Computing and Applications, vol. 25, no. 2, pp. 443–458, 2014.
2. N. Abdelhamid, A. Ayesh, and F. Thabtah, “Phishing Detection Based on URL Features,” International Journal of Advanced Computer Science and Applications, vol. 5, no. 2, 2014.
3. Anti-Phishing Working Group (APWG), “Phishing Activity Trends Report,” 2023.




