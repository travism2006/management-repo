
<h1 align="center">Engineering Sandboxes and Prototypes</h1>

### Magpytest | Pre-Procurement Magnetic Field Simulation (2021)
<ul>
  <li><strong>Problem</strong>: Choosing from a vendor catalog, I needed to source precise permanent magnets without clear visibility into flux strengths, flux interactions, multi-body magnetic layouts and how multi-axial positioning would interact in physical space. </li>
  <li><strong>Sandbox</strong>: Developed a lightweight computational simulator, utilizing numpy and magpylib, to create geometric magnetic bodies (boxes and cylinders), and mathematically compute absolute B-field vectors</li>
  <li><strong>Rationale</strong>: Handled the coordinate grid and field math cleanly using vectorized NumPy array transformations instead of slow processing loops.</li>
  <li><strong>Outcome</strong>: Leveraged Matplotlib to generate 2D/3D plots and system geometries, establishing a visual sanity check to verify component positioning and field strength before finalizing the hardware order.</li>
  <li><strong>Status</strong>: Archived (success). Written as a single-use decision-making tool rather than production software.</li>
</ul>
&nbsp;
