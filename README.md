# syblab_device_list

## :link: Repository URL
| Device | Repository URL |
|----------|----------------|
| Suona | [suona_ros2](https://github.com/aquasf14/suona_ros2.git) |
| Lucia | [lucia_spina](https://github.com/iHaruruki/lucia_spina.git) |
| Spina | [spina_pkg](https://github.com/iHaruruki/spina_pkg.git) |
| Tatto | [tatto_pkg](https://github.com/iHaruruki/tatto_pkg.git) |
| Cibo | [cibo_ros2](https://github.com/iHaruruki/cibo_ros2.git) |
| Orale | [orale_pkg](https://github.com/iHaruruki/orale_pkg.git) |
| Mano | 🙃 Comming soon |
| Occhi | [occhi_docs](https://github.com/iHaruruki/occhi_docs.git) |
| Memoria | [Memoria2](https://github.com/keidep/Memoria2.git) |
| Camina | [camina_ros2](https://github.com/iHaruruki/camina_ros2.git) |
| Mani | [Mani](https://github.com/iHaruruki/Mani.git) |

## :id: ROS_DOMAIN_ID

| Device | NUC | ROS_DOMAIN_ID |
|--------|-----|---------------|
| Suona | 29 & 31 $ 40 | 50 |
| Lucia & Spina | 39 & 41 & 25 | 30 |
| Tatto | - | 30 |
| Cibo_1 | 30 & 36 & 42 | 10 |
| Cibo_2 | 32 & 37 & 42 | 20 |
| Orale | 14 | 60 |
| Mano | 28 | 90 |
| Occhi | 26 | 20 |
| Memoria | Lenovo Tablet | - |
| Camina | 34 & 35 | 40 |
| Mani | 38 & 40 | 80 |

How to change `ROS_DOMAIN_ID`
```bash
export ROS_DOMAIN_ID=1
```

> [!TIP]
> [The ROS_DOMAIN_ID](https://docs.ros.org/en/jazzy/Concepts/Intermediate/About-Domain-ID.html)

## 🧯 Troubleshooting

### ROS2 の通信がうまくいかないとき

1. 起動中の`Topic`を表示する
```bash
ros2 topic list
```
2. 通信相手のIPアドレスを調べる
```bash
ip a
```
3. 疎通確認
```bash
ping 10.20.162.xxx
```