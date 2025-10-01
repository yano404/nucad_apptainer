# NuCAD in Apptainer

## Usage

1. Clone this repository.
  ```
  git clone https://github.com/yano404/nucad_apptainer.git
  ```

2. Build SIF container.
  ```
  cd nucad_apptainer
  apptainer build nucad.sif nucad.def
  ```

3. Run the container.
  ```
  apptainer run nucad.sif
  ```

4. Visit http://localhost:54321 in your web browser.
   You will see Jupyter Lab running on the port.
