## Person 1

### Assigned Tasks:
- **Task 1.2: Scaling Matrix**
  - Derive the 2×2 scaling matrix
  - Implement `get_scaling_matrix(scale_factor_x, scale_factor_y)`
  - Apply scaling to vectors and restore scaled_sheep.png

- **Task 1.4: Translation Matrix**
  - Explain translation using homogeneous coordinates
  - Implement `get_translation_matrix(translation_factor_x, translation_factor_y)`
  - Apply translation to vectors and restore translated_sheep.png

---

## Person 2

### Assigned Tasks:
- **Task 1.3: Shear Matrix**
  - Derive the horizontal shear matrix
  - Implement `get_horizontal_shear_matrix(factor)`
  - Apply shearing to vectors and restore sheared_sheep.png

- **Task 1.6: Mirror Symmetry**
  - Explain vertical mirror symmetry transformation
  - Implement `get_vertical_mirror_matrix()`
  - Apply mirroring to vectors and restore mirrored_sheep.png

---

## Person 3

### Assigned Tasks:
- **Task 1.1: Image Preparation**
  - Load and resize images
  - Explain image representation (shape, dimensions, color channels)
  - Understanding of transformation matrix concept

- **Task 1.5: Rotation Matrix**
  - Derive the rotation matrix using trigonometry (sin, cos)
  - Implement `get_rotation_matrix(phi)` with angle conversion
  - Apply 45° rotation to vectors and restore rotated_sheep.png
  - Work with `cv.warpAffine()` function parameters

---

## Person 4

### Assigned Tasks:
- **Task 2: Perspective Shift (Homography)**
  - Work with img2.jpg
  - Understand homography matrices (3×3 projective transformations)
  - Apply perspective transformations
  - Use `cv.getPerspectiveTransform()` or `cv.findHomography()`
  - Synthesize perspective-free views from angled photos

---

## General Responsibilities

### Individual Responsibilities:
1. Write theoretical explanations for assigned transformations in LaTeX format
2. Test code thoroughly with multiple test cases
3. Verify visual results match expected transformations
4. Comment code clearly
5. Document any issues encountered

### Shared Responsibilities:
1. One person should be designated to combine all work into the final notebook
2. All team members should review the complete notebook before submission
3. Everyone should understand all transformations for the oral defense
4. Work breakdown section must be filled out with accurate effort estimates

---

## Important Notes

### General Guidelines:
- Start with the theoretical explanation - understanding the math makes coding easier
- Use numpy for matrix operations: `np.array()`, `np.dot()` or `@` operator
- Test with simple vectors first before applying to images
- OpenCV uses BGR color format, not RGB
- The coordinate system has origin at top-left corner
- Pay careful attention to angle units (degrees vs radians) for rotation tasks
- Be prepared to explain your work in detail during oral defense
