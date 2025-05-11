# Лабораторные работы по предмету Методы, средства и технологии мультимедиа МАИ

- **Выполнил:** Абдувохидо Э.А.
- **Группа:** М8О-408Б-21

В репозитории хранится 3 файла `ipynb`, в которых находятся решения лабораторных работ.

# Ссылки на google colab:
[6 лабораторная](https://drive.google.com/file/d/1zX-pOdcw-WtDAjemgud5TMtYKCTUixeZ/view?usp=sharing)
[7 лабораторная](https://colab.research.google.com/drive/1gG4oYc_--e_yb4ZVikvaaqe9KluRTRS1?usp=sharing)
[8 лабораторная](https://colab.research.google.com/drive/14W44ugg4vZmQxcRdpRmsaUm48u9_SLxA?usp=sharing)

# Метрики

- Pixel Accuracy
- Mean IoU

## Результаты

<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <!-- Секция CNN -->
    <tr>
        <td rowspan="2">Сверточные нейронные сети (CNN) - torchvision</td>
        <td>Классификация</td>
        <td>0.8259 (ResNet-50)</td>
        <td>0.8748 (ResNet-50 + аугментации)</td>
        <td>0.8598 (Vision Transformer)</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.78</td>
        <td>0.81</td>
        <td>0.76</td>
    </tr>
    <!-- Секция UNet -->
    <tr>
        <td rowspan="2">UNet (segmentation_models.pytorch)</td>
        <td>Классификация</td>
        <td>0.92</td>
        <td>0.94</td>
        <td>0.88</td>
    </tr>
    <tr>
        <td>Сегментация</td>
        <td>0.7492 (UNet-ResNet34)</td>
        <td>0.8043 (UNet-SegFormer-B4)</td>
        <td>0.44</td>
    </tr>
</table>
