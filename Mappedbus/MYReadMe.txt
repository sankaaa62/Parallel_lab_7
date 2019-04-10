1. Если на Win, необходимо создать папку C:/tmp.
2. В консоли переходим в папку с Lab_7\Mappedbus\test\io\mappedbus
3. Вводим команду запуска Writer:
	java -cp mappedbus.jar io.mappedbus.sample.object.ObjectWriter 0
4. Затем запускаем Reader:
	java -cp mappedbus.jar io.mappedbus.sample.object.ObjectReader
5. Видим как полетели сообщения.
6. При желании можно создать необходимое количестово Writer(ов) с различными ключами:
	java -cp mappedbus.jar io.mappedbus.sample.object.ObjectWriter N
	,где N ключ.
7. PerformTEst запускается из той же папки, следующими командами:
	1 консоль) rm -rf /tmp/test;java -cp mappedbus.jar io.mappedbus.perf.MessageReader /tmp/test
	2 консоль) java -cp mappedbus.jar io.mappedbus.perf.MessageWriter /tmp/test
8. Результаты тестирования на моем компьютере представленны на скриншоте по адресу:
	Lab_7\Mappedbus\Result-PerformTest.png