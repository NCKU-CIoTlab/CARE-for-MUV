# demo

[![IMAGE ALT TEXT](http://img.youtube.com/vi/BLUcD01N27M/0.jpg)](https://www.youtube.com/watch?v=BLUcD01N27M "CARE-for-MUV")


# install




# execute

- windows

>Examining Input Parameters
```shell
 .\Interface_windows.exe --help
```

>test single image
```shell
 .\Interface_windows.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input test_data/FILM_1/IMG_1.png --output output.png
```

>test film dir
```shell
.\Interface_windows.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input_film test_data/FILM_1 --output_film output.mp4
```

- Linux
>Examining Input Parameters
```shell
 ./Interface_linux.exe --help
```

>test single image
```shell
 ./Interface_linux.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input test_data/FILM_1/IMG_1.png --output output.png
```

>test film dir
```shell
./Interface_linux.exe --yolo_weights weight/flower_weight.onnx --midas_weights weight/midas_v21_small_256.pt --bl_weights weight/bl_weight.pth --up_weights weight/up_weight.pth --input_film test_data/FILM_1 --output_film output.mp4
```
