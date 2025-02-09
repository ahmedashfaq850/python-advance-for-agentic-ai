virtual environment setup on Windows
- conda create -p myenv python===3.12
- conda activate myenv/

virtual environment setup on Mac
- python3 -m venv myenv
- source myenv/bin/activate

Install Packages using requirements.txt file 
- pip install -r requirements.txt

if got any errors with respect to kernel 
- pip install ipykernel


if we create file under src folder which means now src now become package now be able to import anything from anywhere
- __init__.py 