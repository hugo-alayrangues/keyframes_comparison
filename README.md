# Keyframes comparison for Subliminal Chrome Extension project

- Current method : keyframes are modifying the **box-shadow** property
- Problem : modifying this property is a very resource-intensive process
- Solution : set a static **box-shadow** and use keyframes to modify the opacity only
