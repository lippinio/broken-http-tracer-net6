Run 

docker build -f ConsoleApp6/Dockerfile ConsoleApp6/. -t consoleapp6


docker build -f ConsoleApp5/Dockerfile ConsoleApp5/. -t consoleapp5


docker run -it --rm consoleapp5

docker run -it --rm consoleapp6