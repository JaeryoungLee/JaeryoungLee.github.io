---
title: Regional Optimization of NeQuick, an Ionospheric Model
summary: This is an iono page
date: 2024-09-14
authors: 
- admin

image:
  caption: 'Image credit'
  focal_point: ""
  preview_only: true

---
<span style="font-size:80%">

## Ionospheric Modeling using GNSS measurements<br/>: Regional Optimization of NeQuick-G Model for Improved TEC Estimation

<details open>
  <summary>Summary</summary>

  **Motivation**
  - To improve the accuracy of GNSS positioning by optimizing the estimation of ionospheric delay, particularly in the regional area, where standard global models struggle due to large TEC gradients during high solar activity.

  **Methods**
  - Processed GNSS measurement data in RINEX format using MATLAB, to derive ionospheric delays at each user-satellite links.
  - Optimized the Az parameters of the NeQuick-G ionospheric model using polynomial fitting and the least squares method.


  **Results**
  - The optimized Az parameters reduced TEC estimation errors by up to 88.16% during a geomagnetic storm in May 2024, achieving greater accuracy compared to the Galileo’s broadcast parameters.
  - Further experiments during low and high solar activity confirmed that improvements were most significant during high solar activity, demonstrating better handling of TEC variations in the regional ionosphere.


  **What I’ve Learned**
  -  Gained insights into the application of polynomial fitting and optimization techniques in MATLAB.  
  - RINEX data processing techniques that computes TEC from raw GNSS data. 
  - How a single-frequency GNSS receiver corrects the ionosphere model using models such as NeQuick of Galileo and Klobuchar of GPS.

  **Publications**
  - Journal 
  - Conference Poster
</details>
---

GNSS signals, traveling from satellites in space to receivers on Earth, experience ionospheric delay due to refraction caused by ionized particles in the ionosphere. Accurately estimating ionospheric delay is crucial for precise GNSS positioning. It can also provide useful data for Earth observation, known as remote sensing.

The ionospheric delay is determined by the Total Electron Content (TEC) along the user-satellite link. Ionospheric modeling is a technique used to estimate TEC values. **NeQuick**, Galileo’s ionospheric model, creates a TEC map based on the Az index, which represents the effective ionospheric level. The Az index is expressed as a second-order polynomial in terms of MODIP, the geomagnetic latitude at the receiver. The three Az parameters, (a0, a1, a2), are broadcast to users through Galileo’s daily navigation messages.

*diagram*

The regionally optimized Az parameters were derived through polynomial fitting, using the least squares method. The proposed algorithm is shown below. The goal is to find the optimal Az parameters that minimize the RMS error between the modeled TEC values and the observed TEC values. In this research, the TEC observations were calculated from single-frequency GNSS raw measurement data in RINEX format, processed in MATLAB. The data was provided by the International GNSS Service (IGS) and NASA. The Nelder-Mead Simplex algorithm was used for optimization.

*diagram*

The experiment, conducted using GNSS measurements from May 10-12, 2024, during a geomagnetic storm, showed a significant reduction in TEC estimation errors, with a maximum RMS error reduction of 88.16%—from 15.54 to 5.83 TECU. The following TEC map demonstrates that the optimized Az parameter models the actual ionosphere more accurately compared to the broadcast parameters.

*diagram*

To further evaluate the impact of the optimized Az parameters, additional experiments were performed during low solar activity in 2019 and high solar activity in 2023. The results demonstrated that the improvements were most significant during high solar activity, as the optimized Az coefficient better captured the large TEC variations in the regional ionosphere. This shows that the proposed method for NeQuick G effectively models various ionospheric conditions in local areas, with potential applications in improving GNSS performance by creating different ionospheric scenarios.

*diagram*

</span>

