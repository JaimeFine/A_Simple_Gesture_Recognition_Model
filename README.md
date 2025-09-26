> ⚠️ **Project Migrated**  
> This project has been moved to [My_Embedded_System_Projects](https://github.com/yourusername/My_Embedded_System_Projects/tree/main/Picamera_Control_Python).  
> No further updates will be made here.

# A Simple Gesture Recognition Model

This is a gesture recognition project built using a Raspberry Pi 4, a PiCamera, and two servo motors. It's currently a work in progress — not just a toy demo, but something I want to evolve into a meaningful and practical system.

The source code is currently split across modules, but integration is planned for future updates.

---

## Repository Structure

- `Servos Control/`  
  C++ code for controlling two servo motors via GPIO on the Raspberry Pi. It demonstrates basic motor coordination and GPIO manipulation — ideal for early robotics experiments or embedded systems prototyping.

- `Camera Control/`  
  Python code using PiCamera and OpenCV to capture images and perform basic gesture recognition. Currently uses TensorFlow, but may switch to PyTorch in future iterations.

---

## Future Plans

- Merge servo and camera control into a unified system
- Improve gesture recognition accuracy
- Replace TensorFlow with PyTorch for better flexibility
- Add real-time feedback from servos based on gesture input
> **Notification:**
> The project might be able to continue in or after October, since my focus has shifted from ML to system programming and algorithms, which aligns with my coursework this term.

---

## Notes

- The PiCamera used is the most basic model — keeping it budget-friendly.
- This project is designed to be more than just a beginner’s exercise. The goal is to build something useful, adaptable, and open to future expansion.

---

## Tech Stack

- Raspberry Pi 4
- C++ (for servo control)
- Python + OpenCV
- TensorFlow (tentative)
