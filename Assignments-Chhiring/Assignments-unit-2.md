# Unit 2 All Assignments
## Question Contents:
1. What is signal? Define analog and digital signal.
2. Differentiate between bandwidth, throughput, and speed with example?
3. What is the theoretical data transfer rate(bps) in the medium of 1000Mhz bandwidth?
4. What is transmission impairements? Describe each factors?
5. Describe types of Media?
6. What is modulation and demodulation and its importance in data communication?
7. Describe various types of switching in network communicaiton?
8. What is multiplexing and its usage?

## Solutions
## 1. What is Signal? Define analog and Digital Signal.
Signal is a time varying parameter. Signal represent the variation of a quatity over-time, and it can be continous or discrete. Usually a time-varying parameter is voltage that is an electromagnetic or electrical current that carries data from one system or network to another.

* Analog signal are continous-time signal menaing there is smooth variations over time. It is represented by continouse waveform.

* Digital signal are discrete sequences of values. There is finite set of specific value, for example in usually binary we have 5 volt as 111. 

---

## 2. Differentiate between bandwidth, throughtput and speed with example.
|Bandwidth      |Throughput       |Speed                |
|---------------|-----------------|---------------------|
|Bandwidth refers to the maximum capacity of a medium to transfer data. For example, a 80Mbps cable denotes that at max the cable can transmit 80 Mega bits of data per second|Throughput refers to the rate at which a network or a medium can succesfully transfer data within a given period of time. For example, in a 80Mbps cable the throughput of that cable is slightly less than 80Mbps because the medium or the network is affected by real world phenomenons like transmission imparement| A General term that can be used to refer to both bandwidth or throughput depending upon the situation. For example, a cable with 80Mbps bandwidth can be cosidered the speed of that cable is 80Mbps|

---

## 3. What is the theoretical data transfer rate(bps) in the medium of 1000Mhz bandwidth?
  In a perfect scenario, where each hertz can transmit 2 bits of information, the maximum data rate is twice the bandwidth.
  For a 1000Mz also a 1Ghz bandwidth channel:
  Datarate(R)=2XBandwidth(B)
  R=2 x 1000Mhz
  R=2 x 10^9bps [1hz=2b]
  R=2 x 1Gpbs
  R=2Gbps
  The theoretical data transfer rate (bps) is 2Gbps
---

## 4. What is Tranmission Imparement? Describe each factor.
Transmission impairment refers to any degradation or distortion that occurs to a signal as it travels through a communication medium or channel. Various factors can contribute to transmission impairment, affecting the quality and integrity of the transmitted data. Common sources of transmission impairment include attenuation, distortion, and noise.

1. Attenuation:
Attenuation is the reduction in signal strength as it travels over a distance. It is primarily caused by the resistance of the medium through which the signal passes, such as a cable or a wireless channel. The longer the distance a signal travels, the more it may weaken or attenuate. 

2. Distortion: 
Distortion occurs when the shape of a signal is altered during transmission. This can be caused by various factors, such as frequency-dependent attenuation, interference, or reflections. Different frequencies within a signal may experience varying levels of attenuation, leading to a distortion in the original waveform.

3. Noise:
Noise is an unwanted and random addition to the signal during transmission. It can be caused by external electromagnetic interference, thermal noise within electronic components, or other sources. Noise introduces additional, unpredictable elements to the signal, making it harder to distinguish the original information.

---

## 5. Describe types of Media?
The Types of Communication media are:
1. Guided Media
2. Unguided Media

1. Guided Media:
Guided media, also known as wired or bounded media, involves the use of physical cables or conductors to transmit data signals from one point to another. Some of the examples are:
* Twisted Pair Cable: Consists of pairs of insulated copper wires twisted together. Commonly used in telephone lines and local area networks (LANs).
* Coaxial Cable: Contains a central copper conductor surrounded by insulation, a metallic shield, and an outer insulating layer.
* Optical Fiber: Uses thin strands of glass or plastic to transmit data as pulses of light.

2. Unguided Media: 
Unguided media, also known as wireless or unbounded media, involves the transmission of data through the air or free space without the use of physical cables.
* Wireless Transmission: Involves the use of electromagnetic waves to transmit data without a physical medium.
* Satellite Communication: Utilizes communication satellites in Earth's orbit to transfer signals between ground stations.
* Microwave Communication: Uses high-frequency radio waves for point-to-point communication, often in line-of-sight configurations.

---

## 6. What is modulation and demodulation and its importance in data communication?
1. Modulation:
Modulation is the process of encoding digital information onto an analog carrier signal for transmission. In other words, it involves varying one or more properties of a carrier wave (such as amplitude, frequency, or phase) to represent digital data. This modulation process allows digital information to be transmitted over analog communication channels, like radio waves or cable systems.

Importance of Modulation:
Compatibility with Communication Channels: 
* Many communication channels, especially wireless ones, are better suited for analog signals. Modulation enables the transmission of digital data over these analog channels.
* Efficient Use of Bandwidth: Modulation techniques help optimize the use of available frequency spectrum, allowing more data to be transmitted within a given bandwidth.
* Long-Distance Communication: Analog signals often have better propagation characteristics over long distances. Modulation facilitates the transmission of digital information over these extended ranges.

2. Demodulation:
Demodulation is the reverse process of modulation. It involves extracting the original digital information from a modulated carrier signal. The demodulation process is crucial at the receiving end to recover the transmitted digital data.

Importance of Demodulation:

* Recovery of Digital Data: Demodulation is essential to retrieve the original digital information from the modulated carrier signal, allowing the receiver to interpret the transmitted data accurately.
* Interference Rejection: Demodulation helps in filtering out unwanted signals and noise that may have been picked up during transmission, improving the signal-to-noise ratio.
* Signal Decoding: Demodulation allows the receiver to interpret the varying properties of the carrier signal and reconstruct the original digital signal for further processing.

---

## 7. Describe various switching types in network communication.
1. Circuit Switching:
In circuit switching, a dedicated communication path or circuit is established between two devices for the entire duration of their conversation. Once the circuit is established, the devices can communicate without contention. This method is commonly associated with traditional telephone networks. It is predictable and has constant delay, mostly suitable for continuous communication like voice calls.

2. Packet Switching:
In packet switching, data is divided into small packets before transmission. Each packet is sent independently and may take different routes to reach the destination. Packets are reassembled at the destination. This is the basis for data communication on the internet.

3. Message Switching:
In message switching, the entire message is treated as a single unit and is transmitted from source to destination.Messages are stored and forwarded between switching nodes along the route to the destination.

---