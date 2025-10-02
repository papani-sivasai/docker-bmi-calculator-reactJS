# React + Vite

BMI-Calculator React + Vite 

Install the dependencies

```console
npm install
```
Run the app locally

```console
npm run dev
```
If Docker is installed, try running the docker conatiner instead of running the project locally.

Build a docker image from Dockerfile
```console
docker build -t bmi-calculator .
```

Once the image is ready, run the containerr

```console
docker run -it -p 5173:5173 --name BMI-Calculator bmi-calculator
```

Cheerss, now open the localhost and see the magic
```console
http://localhost:5173
```
