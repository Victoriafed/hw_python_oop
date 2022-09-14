# class InfoMessage:
    """Информационное сообщение о тренировке."""
    def get_message():
        print(f'Тип тренировки: {training_type}; 
         
       Длительность: {duration.3f} ч.; 
            Дистанция: {distance.3f} км; 
            Ср. скорость: {speed.3f} км/ч; 
            Потрачено ккал: {calories.3f}')
