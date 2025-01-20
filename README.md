# Demo

[![IMAGE ALT TEXT](http://img.youtube.com/vi/BLUcD01N27M/0.jpg)](https://www.youtube.com/watch?v=Lw8ilsT-r08 "CARE-for-MUV")


# Installation

>Download the appropriate operating system executable file
https://drive.google.com/drive/folders/1Facz_7lqcRbamWERzlLP19PYeVjPTqw0?usp=drive_link

# Execution

- Windows

>Examining Input Parameters
```shell
 .\Interface_windows.exe --help
```

>Test Single Image
```shell
 .\Interface_windows.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input test_data/FILM_1/IMG_1.png --output output.png
```

>Test Film Directory
```shell
.\Interface_windows.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input_film test_data/FILM_1 --output_film output.mp4
```

- Linux
>Examining Input Parameters
```shell
 ./Interface_linux.exe --help
```

>Test Single Image
```shell
 ./Interface_linux.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input test_data/FILM_1/IMG_1.png --output output.png
```

>Test Film Directory
```shell
./Interface_linux.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input_film test_data/FILM_1 --output_film output.mp4
```
