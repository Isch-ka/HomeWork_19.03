### Данный репозиторий был создан с целью выполнения домашнего задания
<hr>

1. Дополните этот файл инструкциями только по работе с удаленными репозиториями<br>
2. Отправьте pull request<br>

Что бы сохранить к себе чей-то репозиторий, нужно жмать Fork, который должен находится выше от него (чужого репозитория).

После того, как чужой репозиторий теперь ваш, и вы хотите с ним работать через VS Code, вам надо их связать! Для этого заходите в VS Code и пишите в терминале ```git clone (ссылка на репозиторий, который хотите привязать)```.

Теперь, когда репозиторий привязан и отображается у вас в VS Code, переключитесь на него командой ```cd (имя репозитория)```, чтобы потом редактировать.

Это команды, которые переносят отредактированную локально (в VS Code) информацию на Github:
* ```git remote add origin https://github.com/Isch-ka(твоё имя на Github)/test(имя твоего репозитория).git```
* ```git branch -M main```
* ```git push -u origin main```

Это командф, которая перенесёт отредактированную на Github информацию в VS Code, а также сольёт всю информацию в единую:
* ```git pull```
