[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/kzkUPShx)
# a14g-final-submission

    * Team Number: 5
    * Team Name: Pruduct Scanner
    * Team Members: Tianshu Wang & Jin Qian
    * Github Repository URL: 
    * Description of test hardware: (development boards, sensors, actuators, laptop + OS, etc) 

## 1. Video Presentation
<div align="center">
  <a href="https://www.youtube.com/watch?v=oSgTU4lZSk4">
    <img src="https://img.youtube.com/vi/oSgTU4lZSk4/0.jpg" alt="Video Thumbnail" width="500">
  </a>
</div>


## 2. Project Summary
### Device Description
Our device serves as a supermarket product scanner, allowing customers to scan QR codes to access item information such as location, name, and stock quantity displayed on an LCD screen. Supermarket staff can monitor the products scanned by customers and their respective locations via the terminal web page. Moreover, employees can also track the temperature and humidity within the supermarket to assess if environmental adjustments are necessary.

### Inspiration
The inspiration for this product mainly came from what we saw in supermarkets with large indoor areas (such as Costco and Walmart). When we shop in these supermarkets, we often encounter the situation where we want to buy a small product, but it is difficult to find the product because the supermarket is too large. Therefore, our team wants to design a device that can scan the product's QR code. After scanning the QR code, the specific location of the item you are looking for, as well as the price and remaining quantity information can be displayed. Additionally, this product has a built-in temperature and humidity sensor. This information will be sent back to the computers of supermarket staff, allowing them to monitor the environment in the supermarket and adjust the air conditioning temperature in time to ensure that the products are fresh enough to prevent deterioration. Therefore, the target customers of this product are the operators of these large supermarkets. It can be installed on supermarket shopping carts for customers to use.

### Device Functionality
We have designed a device capable of scanning QR codes to retrieve product information while simultaneously monitoring indoor temperature and humidity. The data collected by this device can be transmitted over the network and displayed on the terminal web page using Node-RED. Our device consists of two sensors and two actuators. The sensors include an SHTC3 temperature and humidity sensor and a QR code scanner, while the actuators comprise a vibrating motor and a color LCD screen.

The overall workflow of our product is as follows:
1. When a customer uses the device to scan a QR code, the QR code scanner identifies the scanned QR code and provides vibration feedback to the customer using the vibrating motor.
2. The information retrieved from the scan is displayed on the LCD screen, showing the product's location, name, and inventory quantity.
3. The location information of the scanned items is also uploaded to the Node-RED UI interface, allowing access to this information via devices such as computers or smartphones.
4. Finally, the SHTC3 sensor installed within our device continuously monitors the temperature and humidity of the supermarket. This information is uploaded to the Node-RED UI interface for display. Additionally, if the temperature exceeds a certain threshold or the humidity reaches a high level, a pop-up warning will appear on the page, alerting staff to adjust the air conditioning settings in that area.

## 3. Hardware & Software Requirements

## 4. Project Photos & Screenshots
