# System Architecture

- 전체 구조
![전체 구조](../assets/system_structure.png)

## 발사대

![발사대 구조 설계](../assets/class_Launcher.png)

## MFR

![MFR 구조 설계](../assets/class_MFR.png)

## 미사일

![미사일 구조 설계](../assets/class_Missile.png)

<details>
<summary>미사일 </summary>
<img alt="미사일 설계 고찰" src="../../assets/class_Missile_old.png">
<p1>
미사일의 존재 의의<br>
표적을 추적하여 섬멸할 수 있어야 하는 것.<br>
표적을 추적할 수 있어야 한다. -> 추적을 하려다 보니 항법이 필요한 것이다.<br>
<br>
정리: 항법은 표적 추적의 하위 비즈니스 룰이다.
</p1>
</details>

## ECS 설계

![ECS 구조 설계](../assets/class_ECS.png)

## Gateway 설계

![Gateway 구조 설계](../assets/class_Gateway.png)