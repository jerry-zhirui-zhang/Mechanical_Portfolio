# Lightweight Structural Design

## Summary

I designed, built, and destructively tested lightweight bridge and tower structures with the goal of carrying the full 15 kg competition load while using as little material as possible. I used CAD and basic FEA to compare different designs and identify likely weak points, then built and physically tested each structure to see how it actually failed. Over roughly 30 bridge iterations, I kept changing member sizes, bracing, materials, and joints until the design became nationally competitive.

### Key Results

- Built a **5.65 g bridge that carried the full 15 kg load**, giving an efficiency of approximately **2,655**
- Finished **top 10 nationally**
- Developed and destructively tested **30+ bridge designs and roughly 10 tower designs**
- Used **CAD, FEA, and physical testing** together to guide design changes
- Used **high-speed video** to analyze buckling, shear, joint, and tension failures
- Designed **3D-printed assembly jigs** to improve consistency between builds


## Bridge \& Tower Designs

<table>
  <tr>
    <td width="50%" align="center">
      <img width="1766" height="927" alt="Screenshot 2026-10-06 011952" src="https://github.com/user-attachments/assets/21a79c76-2755-4708-aa1a-b8e64a643ffd" />
    </td>
    <td width="50%" align="center">
      <img width="3024" height="4032" alt="IMG_1779-2" src="https://github.com/user-attachments/assets/1e1c6d98-2e61-46fb-ba60-dc79bc2a7b46" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Bridge</b><br>
      <i>5.65 g structure that carried the full 15 kg load.</i>
    </td>
    <td align="center">
      <b>Tower</b><br>
      <i>Later structural design using the same material-selection and destructive-testing process.</i>
    </td>
  </tr>
</table>

<br>

## Design Process

**CAD → FEA → Fabricate → Load Test → Analyze Failure → Redesign**

- I started by comparing different geometries, member sizes, and bracing layouts before committing to a physical build.
- I used basic FEA to identify areas that were likely to become weak points, then compared those predictions against what actually happened during destructive testing.
- The real structures did not always fail where I expected, so the physical results became the main input for the next iteration.

### Load Testing

<!-- DRAG YOUR BEST FAILURE VIDEO HERE -->

*Destructive testing used to identify where failure started and what needed to change in the next design.*


## Material Selection

- I sorted wood by **species, density, cross-section, and intended location** instead of treating every piece of wood the same.
- I primarily used lightweight **balsa for compression members** and denser **basswood for tension members**, where the extra strength was worth the added weight.
- Because balsa absorbs moisture easily, I also experimented with oven-drying the wood and storing it with silica gel before testing. In some builds, I saw weight reductions approaching roughly **1 g** without an obvious decrease in load capacity.
<img width="4032" height="3024" alt="IMG_0503" src="https://github.com/user-attachments/assets/e876ab9c-49c2-4dec-ad30-74f3dd1b6f01" />

<p align="center">
  <i>Balsa and basswood sorted by size, density, and intended structural role before fabrication.</i>
</p>


## Fabrication \& Jigs

- I designed **3D-printed jigs** to keep the bridge geometry and member placement consistent during assembly.
- Since the structures weighed only a few grams, small alignment errors or excess glue could noticeably affect both weight and load capacity.
- The jigs made it easier to compare designs because I could build each iteration more consistently instead of introducing new manufacturing differences every time.

<table>
  <tr>
    <td width="50%" align="center">
      <img width="487" height="610" alt="Screenshot 2026-10-06 012443" src="https://github.com/user-attachments/assets/37bed3e6-b4a2-4b7f-b002-51be0396154b" />
    </td>
    <td width="50%" align="center">
      <img width="361" height="408" alt="Screenshot 2026-10-06 012656" src="https://github.com/user-attachments/assets/a0480f72-c8b0-42a4-b108-be78281f2927" />

    </td>
  </tr>
  <tr>
    <td align="center">
      <i>3D-printed jig used to control geometry during bridge assembly.</i>
    </td>
    <td align="center">
      <i>3D-printed Jig used to control geometry during tower assembly.</i>
    </td>
  </tr>
</table>

<br>

## Design Iteration
- I went through **30+ bridge designs and around 10 tower designs**, using each failure to guide the next iteration.
- **Buckling failures** usually led me to increase balsa density, change grain selection, or adjust member geometry. I often used stiffer C-grain balsa for heavily loaded compression members.
- **Joint failures** were often caused by poor glue coverage or insufficient curing, so I became much more consistent with joint preparation and allowing at least 24 hours to cure.
- **Tension and shear failures** pushed me to reconsider material choice, member size, or the load path.
- Over time, I focused less on making everything stronger and more on understanding **exactly why it failed** and only adding weight where it was needed.

<img width="854" height="631" alt="Screenshot 2026-10-06 013154" src="https://github.com/user-attachments/assets/158cf7b7-6fd7-4eff-98c5-58acd1dd7d3f" />

<p align="center">
  <i>A portion of the bridge and tower iterations built while refining member sizing, bracing, material placement, and joints.</i>
</p>


## Outcome \& Takeaways

- This project was where I really learned to design around **failure**. Instead of seeing a broken bridge as just a bad test, I started treating the exact failure location as information for the next design.

- After testing so many structures, I started thinking much more about **load paths and efficiency**. Adding material everywhere could make the bridge stronger, but it would also hurt the score, so the real challenge was figuring out exactly where the material was actually needed.
