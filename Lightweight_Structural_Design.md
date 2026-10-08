---
---

# Lightweight Structural Design

## Summary

I designed, built, and destructively tested lightweight bridges and towers with the goal of carrying the full 15 kg load while using as little material as possible. Across 30+ bridge designs and around 10 tower designs, I used CAD, basic FEA, material selection, and physical failure testing to keep improving each structure. My best bridge eventually weighed **5.65 g while carrying the full 15 kg load**, reaching an efficiency of about **2,655** and finishing **top 10 nationally**.

### Key Results

- Built a 5.65 g bridge that carried the full 15 kg load, giving an efficiency of approximately **2,655**
- Finished **top 10 nationally**
- Developed and destructively tested 30+ bridge designs and roughly 10 tower designs
- Used CAD, FEA, and physical testing together to guide design changes
- Used high-speed video to analyze buckling, shear, joint, and tension failures
- Designed 3D-printed assembly jigs to improve consistency between builds

## Destructive Load Test

<p align="center">
  <video width="650" controls>
    <source src="https://github.com/user-attachments/assets/f05014ae-b994-4db1-a5cf-d6ac19a8d0c7">
  </video>
</p>

<p align="center">
  <i>Destructive load testing used to identify the initial failure location and guide the next structural iteration.</i>
</p>


## Bridge \& Tower Designs

<table>
<tr>
<td width="50%" align="center">
  <img width="100%" alt="Bridge" src="https://github.com/user-attachments/assets/21a79c76-2755-4708-aa1a-b8e64a643ffd" />
</td>
<td width="50%" align="center">
  <img height="350" alt="Tower" src="https://github.com/user-attachments/assets/1e1c6d98-2e61-46fb-ba60-dc79bc2a7b46" />
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

## Material Selection

- I sorted wood by **species, density, cross-section, and intended location** instead of treating every piece of wood the same.
- I primarily used lightweight **balsa for compression members** and denser **basswood for tension members**, where the extra strength was worth the added weight.
- Because balsa absorbs moisture easily, I also experimented with oven-drying the wood and storing it with silica gel before testing. In some builds, I saw weight reductions approaching roughly **1 g** without an obvious decrease in load capacity.

<p align="center">
  <img width="700" alt="Balsa and basswood material selection" src="https://github.com/user-attachments/assets/e876ab9c-49c2-4dec-ad30-74f3dd1b6f01" />
</p>

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
  <img width="85%" alt="Bridge assembly jig" src="https://github.com/user-attachments/assets/37bed3e6-b4a2-4b7f-b002-51be0396154b" />
</td>
<td width="50%" align="center">
  <img width="85%" alt="Tower assembly jig" src="https://github.com/user-attachments/assets/a0480f72-c8b0-42a4-b108-be78281f2927" />
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

<p align="center">
  <img width="700" alt="Bridge and tower design iterations" src="https://github.com/user-attachments/assets/158cf7b7-6fd7-4eff-98c5-58acd1dd7d3f" />
</p>
<p align="center">
  <i>A portion of the bridge and tower iterations built while refining member sizing, bracing, material placement, and joints.</i>
</p>


## Outcome \& Takeaways

- This project was where I really learned to design around **failure**. Instead of seeing a broken bridge as just a bad test, I started treating the exact failure location as information for the next design.

- After testing so many structures, I started thinking much more about **load paths and efficiency**. Adding material everywhere could make the bridge stronger, but it would also hurt the score, so the real challenge was figuring out exactly where the material was actually needed.
