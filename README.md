# EM-Visulization
novel visulization approach to electromagnetic fields

1. **Electric Field Calculation**:
   - The total electric field is computed as a superposition of **dipole fields** and **point charge fields** at each grid point.

2. **Field Strength to Transparency**:
   - The electric field magnitude (vector norm) is calculated at each point.
   - Field strength is normalized and mapped to **opacity (alpha)**: stronger fields have higher opacity.

3. **Field Direction to RGB Colors**:
   - The electric field vector at each point is normalized.
   - Each component is mapped to **RGB colors**: 
     - \( R \): X-component (Red)
     - \( G \): Y-component (Green)
     - \( B \): Z-component (Blue)

4. **3D Grid Rendering**:
   - A 3D grid is created where each point is represented by its RGBA values (color + opacity).
   - Points are visualized as glowing spheres using `PyVista`.

5. **Interactive Visualization**:
   - The rendered field distribution is displayed in 3D space, allowing users to **rotate, zoom, and pan** for detailed exploration of the field's direction and intensity.

**The code is coming soon...**

Here is some examples:
two positive charge
![image](https://github.com/user-attachments/assets/71e071f8-eb1f-49ae-8330-98087a541f1b)

electric dipole
![image](https://github.com/user-attachments/assets/40f232e5-cc47-4f12-afd4-6dcdef8510a6)

complex cases
![image](https://github.com/user-attachments/assets/b02e5a89-d988-4a27-8903-ac6e85fce7ff)
![image](https://github.com/user-attachments/assets/f1bae86a-799a-4cc7-9963-9df508579892)
![image](https://github.com/user-attachments/assets/13a67389-b7ba-4f67-a3e6-b3b53e44864f)


