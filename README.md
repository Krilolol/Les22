# Les22

# AWS - Basic

## 1. Створення та налаштування VPC

### - Створив через консоль AWS VPC з однією публічною та приватною підмережами.
![1](https://github.com/user-attachments/assets/9a0b5fb9-9ac6-4d6a-8075-908fa9254143)



## 2. Налаштування груп безпеки (Security Groups)
![4](https://github.com/user-attachments/assets/369d5a39-5112-4b6c-a008-7e86f8226958)



## 3. Запуск інстансу EC2

### - Створив інстанс EC2 Amazon Linux 2 AMI з типом t3.micro.

### - Прив'язав до публічної мережі.

### - Створив SSH-ключ для доступу до інстансу.
![5](https://github.com/user-attachments/assets/662f3071-546d-44dd-97dc-2fc3f2787a33)

![6](https://github.com/user-attachments/assets/4f51fd6b-5024-4625-b7c6-b90fcdc148aa)

![7](https://github.com/user-attachments/assets/e8786fab-d5f2-403d-a6a9-94750cddfd9b)

## 4. Призначення еластичної IP-адреси (EIP)

### - Створив нову EIP в AWS консолі та прив'язав до створеного інстансу.

![8](https://github.com/user-attachments/assets/775893f5-d27c-4940-adee-c94c87bebb54)


### - Додав в Security Groups правило All ICMP - IPv4 (для ping).
![9](https://github.com/user-attachments/assets/7682866b-7219-4d23-ae70-19ad9b9b66d7)
