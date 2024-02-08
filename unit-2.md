
#  Assignment of Unit 2

## **1. What is signal? Define analog and digital signal.**

### An electrical or electromagnetic quantity (current, voltage, radio wave, micro wave, etc.) that carries data or information from one system (or network) to another is called a signal.

### There are two types of signals are:

* **1. Analog Signal**

A signal which is a continuous function of time and used to carry the information is known as an analog signal. An analog signal represents a quantity analogous to another quantity, for example, in case of an analog audio signal, the instantaneous value of signal voltage represents the pressure of the sound wave.

* **2. Digital Signal**

A signal that is discrete function of time, i.e. which is not a continuous signal, is known as a digital signal. The digital signals are represented in the binary form and consist of different values of voltage at discrete instants of time.


## **2. Differentiate between bandwidth, throughput, and speed with example?**

### **1. Bandwidth**

### Bandwidth is the quantity of data that can be transferred over a network in a given amount of time. It refers to the network/transmission medium's data carrying capability. In computing, the maximum pace of data flow via a particular route is known as the bandwidth. Network bandwidth, data bandwidth, and digital bandwidth are all examples of bandwidth.

### Bandwidth also refers to the frequency range between the lowest and highest attainable frequency. Analog signal bandwidth is measured in Hertz.

### It is always better to have a wide bandwidth because it enables more users/subscribers to access the network at the same time with lesser traffic or network congestion.

### **2. Throughput**

### Throughput is the measurement of the amount of data being transmitted across a network, interface, or channel in a given length of time. Throughput is also known as "effective data rate" or "payload rate". In general, throughput refers to the pace at which something is produced or processed.

### Throughput, also known as "network throughput", is the rate of successful message transmission through a communication channel in communication networks such as Ethernet or packet radio. The data included in these messages may be transmitted through a physical or logical link, or it may transit through a network node.

[Difference between Bandwidth and 
Throughput](https://www.tutorialspoint.com/difference-between-bandwidth-and-throughput)

### **3. Speed**

### The rate of transferring the data is known as Speed. The speed is also measured by Mbps (Megabits per second). The speed of the internet to load web pages, videos, files, etc. is known as Internet speed. Speed is a major factor in the internet for numerous activities such as streaming, uploading, downloading games, etc.

[Difference between Bandwidth and Speed](https://www.tutorialspoint.com/difference-between-bandwidth-and-speed)


## **3. What is the theoretical data transfer rate(bps) in the medium of 1000Mhz bandwidth?**

### The theorrtical data transfer rate in the medium of 1000Mhz bandwidth is 10^9 bits per second(bps), or 1 Gbps(Gigabit per second). The theoretical data transfer rate (in bits per second, bps) in a communication channel is determined by the bandwidth of the channel and the modulation scheme used. The relationship between bandwidth (B) and data transfer rate (R) is given by the Nyquist-Shannon theorem, which states:

**R=2XB**

Where:

* **R** is the data transfer rate in bps,
* **B** is the bandwidth in hertz(Hz).

In your case, if the bandwidth is 1000 MHz, you need to convert it to hertz by multiplying it by 10^6 (since 1MHz = 10^6 Hz.)

B = 1000 MHz X 10^6 Hz/MHz = 10^9 Hz

Now, you can use the  Nyquist-Shannon theorem to find the theoretical data transfer rate:

R = 2 X 10^9 bps

So, the theoretical data transfer rate in a medium with a bandwidth of 1000 MHz is 2 X 10^9 bps.

## **4. What is transmission impairements? Describe each factors?**

### Transmission impairments refer to the difference between the transmitted and received signals in a communication system due to imperfections in the transmission medium. There are three main types of transmission impairments: 

**1.Signal Distortion:** This alters the shape of the signals, especially composite signals. It can be caused by environmental parameters, properties of the transmission medium, and the distance between the transmission end and receiving end. Signal distortion can be further divided into two types:

**Frequency Distortion:** This occurs when frequency components of the signal undergo unequal levels of attenuation, changing the waveshape of the signal.

**Phase or Delay Distortion:** This happens when frequency components of the composite signal propagate through the transmission medium at different velocities, introducing a delay in the signal reaching the receiving end and causing a phase difference between the signal at the receiving end and the transmitting end.


**2. Attenuation:** This is the decrease in signal strength during transmission, making it harder to receive at the other end. It is primarily caused by the environment, which imposes resistance on the signal as it travels through the medium.

**3. Noises:** These are unwanted signals added to the transmitted signal, making it challenging to remove the noise at the receiving end. There are several types of noises, including thermal noise, induced noise, crosstalk, and impulse noise.




## **5. Describe types of Media?**

### Media refers to the physical or virtual channels through which information is transmitted. Media is the main means of communication for people in a society. It can fall under a receipt of information or a way to market, but however it is done, it is communicating something. It refers to the way that messages are delivered to individuals. The goal of media is to communicate the intended message effectively. 

### There are various types of media are: 

**1. Physical Media:**

Physical media refers to the physical components used for transmitting information such as wires, cables and devices like printers and computers. It includes copper wire, fiber optic cable, infrared (IR), radio waves, light beams, and others. The signal carrier in this type of media has a fixed frequency that does not change during
transmission. For examples: Copper Wires, Fiber Optics Cables, Coaxial Cables, Radio Waves, etc.


**2. Virtual Media:**

Virtual media or logical media is an abstraction provided by software
to represent different communication channels. These include serial ports, parallel ports, USB, Ethernet, Token Ring, Firewire, Bluetooth, WiFi, etc., which provide a common interface between computer hardware and applications running on the computer system. In virtual media, the signal carrier’s frequency can vary during transmission, allowing multiple users to share the same channel the signal carrier's frequency may vary depending upon the specific protocol being used. For examples: Internet, Social Media, Streaming Services, etc.




## **6. What is modulation and demodulation and its importance in data communication?**

### **Modulation:** 
Modulation is the process of encoding digital information onto an analog carrier signal for transmission.In other words, it involves varying certain properties of a carrier signal (such as amplitude, frequency, or phase) to represent digital data. The purpose of modulation is to allow the transmission of digital information over analog commmunication channels, which are better suited for long-distance and high-frequency transmission.

### **Demodulation:**
Demodulation is the process of extracting the original digital information from a modulated carrier signal. It is the reverse process of modulation. Demodulation is essential at the receiving end to recover the digital data transmitted over the communication channel.



### Importance in Data Communication:

**1.Compatibility with Communication Channels:** Analog communication channels, such as radio waves and wired connections, are often better suited for long-distance transmission. Modulation allows digital information to be transmitted over these analog channels efficiently.

**2.Bandwidth Efficiency:** Modulation techniques help in utilizing the available bandwidth more efficiently. By modulating a carrier signal, multiple signals can share the same communication channel without interference, allowing for higher data transmission rates.

**3. Reduced Attenuation and Interference:** Analog signals, especially at higher frequencies, can experience less attenuation and interference compared to digital signals. Modulating digital data onto an analog carrier helps overcome these challenges during transmission.

**4. Improved Signal-to-Noise Ratio:** Modulation can enhance the signal-to-noise ratio of a communication system. By shifting the information into a different frequency range (modulation), the signal becomes less susceptible to noise and distortion during transmission.

**5. Long-Distance Communication:** Analog signals, particularly in the radio frequency range, can travel longer distances without significant loss of signal strength. Modulation allows digital information to be transmitted over long distances using these analog channels.

**6. Multiplexing:** Modulation enables multiplexing, where multiple signals can be combined and transmitted over the same channel. This is crucial for efficient utilization of resources in telecommunications.

**7. Versatility:** Different modulation techniques (e.g., amplitude modulation, frequency modulation, phase modulation) offer versatility in adapting to various communication channel characteristics and requirements.


### **7. Describe various types of switching in network communication?**

### **Switching** in network communication refers to the method used to forward data from the source to the destination across a network. There are three main types of switching: 

**1. Circuit Switching:**
 In circuit switching, a dedicated communication path is established between two devices for the duration of their conversation. The path remains reserved exclusively for those devices until the communication is complete.

**Characteristics:**

* Continuous connection during the entire communication session.
* Dedicated resources for the entire duration, even if no data is being transmitted.
* Commonly used in traditional telephone networks for voice communication.


**Advantages:**

* Predictable and consistent performance.
* Low latency for real-time communication.

**Disadvantages:**

* Inefficient use of resources when the connection is idle.
* Scalability challenges for a large number of simultaneous connections.


**2. Packet Switching:**
Packet switching breaks data into small packets and transmits them independently over the network. Each packet can take a different route to reach the destination, and they are reassembled at the destination.

**Characteristics:**

* Data is divided into packets, and each packet contains a portion of the message along with destination information.
* Each packet is transmitted independently and may follow different routes to reach the destination.
* Used in modern computer networks, including the Internet.

**Advantages:**

* Efficient use of network resources as bandwidth is shared dynamically.
* Scalable for a large number of connections.
* Robust and resilient to network failures.


**Disadvantages:**

* Variable latency due to different routes and potential packet reordering.
* Overhead in packet header and processing.


**3. Message Switching:**
Message switching involves the entire message being forwarded from the source to the destination. The message is stored and forwarded through a series of network nodes until it reaches its destination.


**Characteristics:**

* The entire message is treated as a unit and is stored and forwarded through the network.
* Nodes in the network may temporarily store the message before forwarding it to the next node.
* Not commonly used due to its inefficiency compared to packet switching.


**Advantages:**

* Simplicity in terms of message handling.
* Less complex than packet switching in terms of routing and addressing.


**Disadvantages:**

* Inefficient use of network resources, as the entire message must be transmitted before reaching the destination.
* Higher latency for large messages.




### **8. What is multiplexing and its usage?**

### **Multiplexing** is a technique used in telecommunications and computer networks to combine mulitple signals or data streams into a single transmission medium, allowing for efficient use of resources. The Primary goal of multiplexing is to transmit multiple signals over a shared communication channel simultaneously.

### The types of multiplexing are :

* **Time Division Multiplexing (TDM)**
* **Frequency Division Multiplexing (FDM)**
* **Wavelength Division Multiplexing (WDM)**
* **Code Division Multiplexing (CDM)**
* **Spatial Division Mutliplexing (SDM)**

**Usage of Multiplexing:**

* **Efficient Resource Utilization:** Multiplexing allows for the simultaneous transmission of multiple signals over the same communication channel, maximizing the use of available resources.

* **Increased Data Throughput:** By combining multiple signals, multiplexing increases the overall data throughput of a communication channel.

* **Cost Savings:** Multiplexing enables the sharing of infrastructure, reducing the need for additional physical channels and lowering overall costs.

* **Improved Network Efficiency:** Multiplexing is essential for optimizing the efficiency of communication networks, especially in scenarios where multiple users or data streams need to share the same medium.

