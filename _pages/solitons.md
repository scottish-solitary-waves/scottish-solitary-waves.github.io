---
permalink: /solitons
title: "Solitary waves"
excerpt: "Solitons "
author_profile: true
---

      
<details>
  <summary style="font-size:14">
        <b>What are solitary waves?</b>
  </summary>
      <div style="background-color:#f0f0f5">
  <p style="background-color:#f0f0f5">
    Solitary waves are a special class of water waves. For the purposes of this project, they are best defined by a single elevation in the water surface. A soliton will typically span the entire width of a canal. Such a wave is most likely to be seen on its own, upstream of any boat because solitons move faster than the boat that created them and can travel very long distance without changing shape.
  </p>
      </div>
</details>


<details>
  <summary>
        <b>How are solitary waves generated?</b>
  </summary>
    <div style="background-color:#f0f0f5">
    <p style="background-color:#f0f0f5">
    Solitary waves are generated when a vessel enters the so-called trans-critical region in terms of blockage and speed. <br>
          We can express the blockage as $B=A_b/A_c$ where $A_c$ is the canal cross-sectional area and $A_b$ is the boat midship cross sectional area. We also make the speed ($V$) dimensionless by dividing it by the speed of the wave $c=\surd(gh)$, with $g=9.81m/s^2$ and $h$ being the water depth. We call that ratio the depth Froude number $F_h=V/\surd(gh)$ which is  analogous to the Mach number in aerodynamics. The figure below shows the three possible flow regimes: </p>
          <ul style="background-color:#f0f0f5">
  <li>Subcritical: the depth Froude number is below $1$ and steady flow is possible.</li>
  <li>Trans-critical: the depth Froude number can be $F_h>1$ or $F_h<1$, but no steady flow is possible</li>
  <li>Supercritical: the depth Froude number is higher than 1 and steady flow is possible.</li>
</ul>
          <br>
The image below was constructed using:
          $$B_{crit}=1-sin(3arcsin(F_h^{2/3}/2))$$
            
          
  <img src="https://user-images.githubusercontent.com/108955232/187413388-5b0c2df6-e7c6-4cc9-b863-e47dc35ef03f.png" width="70%" height="70%">
             
</div>
</details>


<details>
  <summary>
        <b>What does solitary wave generation look like?</b>
  </summary>
          <p>
     <img src="https://user-images.githubusercontent.com/108955232/187429659-11846900-dc76-466b-b85a-5a3b9a686860.gif" width="100%")
          </p>

</details>
      
<details>
  <summary>
    Next steps
  </summary>
      <div style="background-color:#f0f0f5">
  <p style="background-color:#f0f0f5">
 I will add a calculator that gives the critical blockage for a given depth Froude number
  </p>
      </div>
</details>
