1. ���� �� Win, ���������� ������� ����� C:/tmp.
2. � ������� ��������� � ����� � Lab_7\Mappedbus\test\io\mappedbus
3. ������ ������� ������� Writer:
	java -cp mappedbus.jar io.mappedbus.sample.object.ObjectWriter 0
4. ����� ��������� Reader:
	java -cp mappedbus.jar io.mappedbus.sample.object.ObjectReader
5. ����� ��� �������� ���������.
6. ��� ������� ����� ������� ����������� ����������� Writer(��) � ���������� �������:
	java -cp mappedbus.jar io.mappedbus.sample.object.ObjectWriter N
	,��� N ����.
7. PerformTEst ����������� �� ��� �� �����, ���������� ���������:
	1 �������) rm -rf /tmp/test;java -cp mappedbus.jar io.mappedbus.perf.MessageReader /tmp/test
	2 �������) java -cp mappedbus.jar io.mappedbus.perf.MessageWriter /tmp/test
8. ���������� ������������ �� ���� ���������� ������������� �� ��������� �� ������:
	Lab_7\Mappedbus\Result-PerformTest.png