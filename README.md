# Microservices Assignment

Use virtual python environment pyenv to install flask and other necessary libraries to run the order and user services to
simulate how they work independently similar to microservices 

## To use a virtual environment to manage dependencies for the project

### Create a virtual environment
```bash
python -m venv myenv
```
### Activate the virtual environment
#### On Windows:
```bash
myenv\Scripts\activate
```
#### On macOS/Linux:
```bash
source myenv/bin/activate
```
### Install Flask
```bash
pip install flask requests
```

## Output

### Both services are running on different ports independently

![alt text](image.png)

### Running the Example Requests


#### Creating a User
![alt text](image-1.png)
#### Getting a User
![alt text](image-4.png)
#### Creating an Order
![alt text](image-3.png)
#### Getting the Order
![alt text](image-2.png)