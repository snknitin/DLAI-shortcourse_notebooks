# DLAI-shortcourse_notebooks
Notebooks to test the code for the deeplearning.ai short courses

# Environment Setup
To set up the folder structure, run the following command:

```powershell
@("course1", "course2", "course3") | ForEach-Object { New-Item -ItemType Directory -Path ".\courses\$_\notebooks", ".\courses\$_\data", ".\courses\$_\outputs" -Force }
```
