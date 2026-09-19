# modular-colourblind-camera
A custom Linux-based modular camera system including precision-toleranced 3D printed mechanics, swappable vintage optics, and real-time OpenCV Daltonisation pipeline designed for colourblind accessibility. 

```mermaid
gantt
    title Engineering Development Schedule
    dateFormat YYYY-MM-DD
    axisFormat %m/%d
    
    section Phase 1: Benchtop MVP
    OS, DSI LCD & Boot        :done, 2026-09-19, 0.5d
    Daltonization Math        :done, 2026-09-19, 0.5d
    GPIO Hardware & Wi-Fi     :active, 2026-09-19, 0.5d
    
    section Phase 2: CAD & DFM
    Optical Sled & FFD        :2026-09-17, 1d
    Thermal Ducts & Sled      :2026-09-18, 1d
    Bambu Slicing & Print     :2026-09-19, 1d
    
    section Phase 3: Integration
    Heat-Sets & Wiring        :2026-09-20, 1d
    Optical Calibration       :2026-09-21, 1d
    Thermal Stress Test       :2026-09-22, 1d
    
    section Phase 4: Portfolio
    Aesthetic Trim & Video    :2026-09-23, 1d
    Job Pack & Docs           :2026-09-24, 1d
```