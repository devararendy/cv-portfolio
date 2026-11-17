# **Rendy Devara**  
[📧 rendy_devara@msn.com](mailto:rendy_devara@msn.com) | [🔗 LinkedIn](https://www.linkedin.com/in/rendy-devara-42bb861a2/) | [🐙 GitHub](https://github.com/devararendy) | [☎️ (+62)81285960935](https://wa.me/6281285960935)

---

## **👤 Profile**  

<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/RendyDevara.jpg" alt="Profile Image" width="150" style="border-radius: 50%;">
    <div>
        <ul>
            <li><b>Full Name:</b> Rendy Devara</li>
            <li><b>Email:</b> <a href="mailto:rendy_devara@msn.com">rendy_devara@msn.com</a></li>
            <li><b>Nationality:</b> Indonesian</li>
            <li><b>Phone Number:</b> (+62)81285960935</li>
        </ul>
    </div>
</div>

---

## **📝 Professional Summary**

Backend engineer specializing in low-latency order routing, exchange connectivity, and production-grade trading systems. With 9+ years of experience across software and hardware engineering, I lead high-throughput, latency-sensitive systems that connect brokers to stock exchanges, manage order flow, and support market operations in real time. I focus on technical ownership, operational reliability, and scalable architecture for critical financial infrastructure.

---

## **💡 Skills**

### **Software Skills**
- **Programming Languages:** Go, C++, Python, SQL, Bash Script (Linux / Unix)
- **Communication Protocol / Interface:** TCP, UDP, REST APIs, FIX, OUCH, gRPC
- **Messaging & Data:** Kafka/Redpanda, Redis, PostgreSQL, SQL Server, S3
- **Protocols & Integration:** FIX, OUCH / SoupBinTCP, gRPC / Protobuf, Avro, REST APIs
- **Infrastructure & Observability:** Kubernetes, Docker, Git, ArgoCD, Vault, Grafana, OpenTelemetry, New Relic, K6, GitLab CI, Sonar
- **Engineering Practices:** Low-latency optimization (µs-level), idempotency and recovery design, load testing, gradual rollouts, feature flags, unit testing (Gomega, mocks)
- **Domain Knowledge:** IDX market structure, order lifecycle, exchange connectivity, market operations

### **Hardware Skills**
- **Communication Protocol / Interface:** MQTT, UART, SPI, I2C, LORA, MAVLink
- **Embedded System:** Raspberry Pi, ESP32, ESP8266, STM32, AVR
- **Measurement & Troubleshooting:** Digital Multimeter, Oscilloscope, Signal Analysis, Hardware Debugging
- **Hardware:** PCB Design (EagleCAD, KiCad), 3D Design (Fusion360), UV 3D Printing, CNC Machining
- **Drone & VTOL Systems:** ArduPilot, Betaflight, PX4, Flight Controller Tuning, Propulsion Systems, UAV Integration
- **Frameworks & Tools:** QT Creator, Arduino, mbedOS, STM32CubeIDE

---

## **🏢 Professional Experience**

### **Backend Engineer, Order Routing & Exchange Connectivity**
**Stockbit.com** | 📍 Jakarta, Indonesia  
*Dec 2021 – Present*  
- Technical lead / PIC for exchange connectivity initiatives, including RFC design, technical scoping, task breakdown, MR review, release coordination, and go-live support.
- Own order-related services for transformation, routing, and sending flows across FIX and OUCH integrations, including outgoing/incoming transformers and binary protocol handling.
- Deliver production-ready trading infrastructure with release notes, ArgoCD/Vault configuration, gradual rollouts, alerting, Grafana dashboards, and operational safeguards during market hours.
- Support market operations through IDX mock trading, morning monitoring, fire drills, on-call incident investigation, and manual data correction for stuck or pending orders.
- Mentor engineers through onboarding and knowledge-sharing sessions while contributing to the wider trading stack, including risk, margin, settlement bridges, and pre-queue order workflows.

### **Key Achievements**
- **OUCH protocol adoption (2024–2025):** Designed and implemented the OUCH Order Sender and integration changes, including Router transformers and an encoder/decoder for low-latency trading flows. Rolled out to production gradually from 1% to 100% of traffic.
- **Faster preload and early launch:** Built a preproduce mechanism that reduced backup-write latency and improved early-market launch timing from milliseconds to microseconds.
- **Pre Queue Order Generator performance (2026):** Reduced processing time for 100K mixed orders from ~4 minutes 20 seconds to ~30 seconds after parallelization and indexing, without CPU throttling.
- **FCA market cycle support:** Wrote the RFC and technical design, implemented handling across pre-queue FIX/OUCH launchers and exchange stock workflows, and optimized a sorting slowdown from ~4 seconds to ~1 second.
- **New IDX platform support:** Contributed to FIX design updates and later OUCH version changes required for the new exchange platform.

### **Firmware Engineer**
**PT Mecoindo - Itron** | 📍 South Cikarang, Indonesia  
*Sept 2020 – Nov 2021*  
- Designed firmware and Linux user-space applications for Smart Electric Meters and Modems using Python.
- Created custom Linux builds for embedded systems using Buildroot and Yocto.
- Built Unix/Linux-based tooling to support device development and deployment.

### **Senior R&D Engineer (Team Leader)**
**Ishaan Informatics Pte. Ltd.** | 📍 Jakarta, Indonesia  
*Sept 2017 – Jul 2020*  
- Led a team of 6 engineers to design and deliver airline electronics products for mission-critical use cases.
- Prototyped and validated products such as eTag, BLE Beacon, and ePass, including PCB design, layout, and hardware debugging.
- Implemented RESTful APIs for interfacing hardware with mobile apps and backend systems.
- Conducted hardware verification using oscilloscopes, DMMs, and antenna analyzers.

---

## **⏳ Part-Time Experience**

### **RF Engineer**
**OS-Wifanusa** | 📍 Bandung, Indonesia  
*Jan 2016 – Jun 2016*  
- Developed radio frequency communication devices and battery packs with integrated management systems.

### **Embedded System Engineer**
**Homebrew Partner** | 📍 Jakarta, Indonesia  
*Nov 2014 – Jan 2016*  
- Designed microcontroller firmware for controlling amateur radio interfaces.

---

## **🎓 Education**

### **Bachelor of Computer Engineering**
**BINUS University** | 📍 Jakarta, Indonesia  
*Jun 2013 – Aug 2017*  
- Graduated with honors (GPA: 3.36/4.0)  
- Major: Embedded Systems  
- Relevant Courses: Hardware Engineering, Software Engineering, Data Structures, Algorithms, Database Systems

---

## **🛠️ Projects**

### **Bot Telegram Near ARA Stock (IDX)**
- Built a bot to fetch and filter stocks potentially reaching ARA (max price of the day). Assisted traders in making data-driven decisions by providing timely alerts and critical stock insights. Included information such as Best Bid, Best Ask Price and Volume, Latest PBV, and Percent Gain. Developed in Golang.

### **Truck Scale Software**
- Developed a cross-platform GUI application in C++ for truck weight measurement with integrated features such as digital scale readings, ticket printing, comprehensive reporting, and user account management. Enhanced functionality by incorporating USB camera support to capture and embed truck images into reports during the weighing process.

### **Drone Delivery Service**
- Designed and developed drones from schematics, PCB design, and firmware for aerial package delivery. Capable of carrying 2kg payloads. Firmware written in C++. The quadcopter uses 17-inch carbon propellers and brushless motors for improved energy efficiency. Utilized multiple sensors (gyroscope, accelerometer, magnetometer, barometer, GNSS) with sensor fusion for precise position estimation. Powered by a high-density lithium-ion battery to maximize flight time.

### **FPV Drone**
- Built FPV drones for hobbies and clients, including tiny whoops, 3-3.5 inch whoops, freestyle 5-inch, race drones, and long-range VTOL drones. Equipped with the latest Radio Control protocol (ELRS) for extended range, digital video transmission for clear pilot visuals, and failsafe features with GNSS UBlox M10 for emergency Return to Home functionality. Fully tested before handover to clients.

---

## **🏆 Awards**

- **Technical Award** – The 13th International Robot Olympiad (2011)  
- **2nd Place** – Autonomous Sumo Robot, Robotic Day (2011)  
- **1st Place** – Autonomous Sumo Robot, Robotic Day (2012)  
- **1st Place** – Line Follower Robot, Pesta Rakyat Fisika UI (2011)

---

## **🎨 Interests**

- Open-source contributions
- Stock investment and trading
- Robotics, drone development for industrial applications, and FPV drone innovation

---

## **💼 Portfolio**

Welcome to my portfolio! Here are my featured projects:

### **📁 [MAVVision](https://play.google.com/store/apps/details?id=com.mavvision.app&pcampaignid=web_share) - FPV Video + Mavlink Bridge Over Network**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/MAVVision-app-ss.webp" alt="MAVVision" width="200" style="border-radius: 5%;">
    <div>
        <p>
            <a href="https://play.google.com/store/apps/details?id=com.mavvision.app&pcampaignid=web_share">MAVVision</a> is an app that turn your android into FPV Camera + Mavlink USB telemetry to TCP / UDP bridge. So you can connect RC Car, Drone, VTOL to GCS (QGroundControl, Mission Planner) over WiFI, 4G/5G Network anywhere as long there is internet connection.
        </p>
    </div>
</div>

### **📁 5-inch Freestyle FPV Drone**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/FPV-Freestyle-Drone.jpg" alt="5-inch Freestyle FPV Drone" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A FPV Drone that use STM32 as a brain Consist of FPV Camera with HD DVR, STM32 microcontroller, IMU, GNSS Ublox M10, 32bit ESCs, Brushless Motors. Able to Fly Acrobatics over +120km/h and has Return To Home Failsafe capability.
        </p>
    </div>
</div>

### **📁 24invitation.com - Digital Invitation Service**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/24invitation-DigitalInvitationService.png" alt="24invitation.com - a Digital Invitation Service" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A Website that provide You a Digital Invitation service.
            This a new era for inviting Your beloved guest to Your best Wedding Party. With this website You can easily manage your guest, see their best wishes for You. You can manage it thru Your own dashboard.
            This Website is using Python Django as a backend.
        </p>
    </div>
</div>

### **📁 TruckScale Software**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/TruckScaleSoftware.png" alt="Truck Scale Software" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A GUI Software for Measure Truck Weight & Print Ticket.
            This Software will connect to digital weight scale + load cell sensor. This software will get the weight and print tickets for the Company of each Truck.
            It use encrypted SQL to ensure the data is safe and secure. The user access also can be configured.
            This software can be deployed to macOS, Linux, Windows. This was written in C++
        </p>
    </div>
</div>

### **📁 ESP32 Tiny Drone**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/ESP32-TinyDrone-DrRobot.png" alt="ESP32 Tiny Drone" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A tiny Quadcopter that use ESP32 as a brain. 
            Consist of ESP32 microcontroller, IMU MPU9250 contains Accelerometer, Gyroscope, Magnetometer in single chip, IR VL53l0X sensor for calculating height above ground. The purpose of this drone is to let people learn how to program a drone.
        </p>
    </div>
</div>

### **📁 NanoDLP UV 3D Printer Controller**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/NanoDLP-3D-Printer-Controller.jpg" alt="NanoDLP UV 3D Printer Controller" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A Nano DLP Shield for Raspberry Pi.
            Consist of DRV8825 for driving Z axis, DC booster for driving 50 watt UV LED and atmega8 as a GRBL controller
        </p>
    </div>
</div>

### **📁 SDEx 32bit Flight Controller**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/SDEx-FlightController.jpg" alt="SDEx 32bit Flight Controller" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A DIY Flight Controller of Smart Drone Express.
            Consist of STM32F446RE microcontroller, IMU MPU9250, Barometer MS5611. Programmed in System Workbench (Eclipse Based) C++ with mBed OS
        </p>
    </div>
</div>

### **📁 SDEx Drone Delivery**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/SDEx-DroneDelivery.jpg" alt="433MHz RF Amp 30 Watt" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A Drone for Delivering Package.
            Consist of the DIY Flight Controller (STM32F446RE with mBed OS), Carbon Frame, Brushless motor, ESCs, 17” Carbon Propellers, Li-Ion Battery Pack 6s2p.
        </p>
    </div>
</div>

### **📁 U-Copter Drone**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/UCopter-Drone.jpg" alt="Uni Copter Drone" width="200" style="border-radius: 5%;">
    <div>
        <p>
            An Uni-Copter Drone.
            Similar to Co-axial helicopter, it uses 2 rotors CW and CCW. It Consist of 2 Brushless motors, 6 servos for controlling 2 swashplates, GNSS, Pixhawk Flight Controller, Raspberry Pi 2, Long Range WiFi 2.4GHz WN7200ND and Pi Camera. 
        </p>
    </div>
</div>

### **📁 BINUS - SR01 KRPAI Fire Fighting Robot**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/KRPAI-FireFighitingRobot-BINUS.png" alt="KRPAI Fire Fighting Robot" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A Fire Fighting Robot built when I was on University of BINUS Computer Engineering.
            This robot is for KRPAI Contest. It will search for fire in a room. Consist of UVtron sensor, 8 Parallax Ping sensors, 4 IR Sharp sensors, Gyroscope L3G4200D, servo, DC motors, motor driver, LiPo battery, atmega2560 as a main controller and atmega8 as a sensor controller.  
        </p>
    </div>
</div>

### **📁 OS-Wifanusa - RF Booster 30 Watt**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/433MHz-RF-Amp-30watt.jpg" alt="433MHz RF Amp 30 Watt" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A RF Booster for Long Range Drone.
            Consist of High Power 30 Watt RF amplifier IC to boost RF between 400 MHz - 470 MHz 
        </p>
    </div>
</div>

### **📁 Homebrew Partner - DDS Module Interface**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/HomebrewPartner-DDS-Module.jpg" alt="DDS Module Interface" width="200" style="border-radius: 5%;">
    <div>
        <p>
            An Interface for Amateur Radio.
            Consist of 16x2 display, atmega8 and DDS AD9850 for generating local oscillator. Programmed in C using Atmel Studio 
        </p>
    </div>
</div>

### **📁 SMAN 2 Depok - UAV**
<div style="display: flex; align-items: center; gap: 20px;">
    <img src="./resource/image/UAV-SmadaRobo.jpg" alt="SmadaRobo UAV" width="200" style="border-radius: 5%;">
    <div>
        <p>
            A Fixwing UAV Drone, built when I was on Senior High School at SMAN 2 Depok for IARC Contest.
            This Drone equiped with brushless motor and 14 inch propeller. With 180cm wingspan to increase efficiency. With GNSS to be able to locate current position of the Drone. Equiped with FPV camera and capable to send realtime video.
        </p>
    </div>
</div>

---