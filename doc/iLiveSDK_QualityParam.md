## ֱ�������ص�����������

```json
{
	"exeCpuRate": 3456,		// Ӧ��CPUʹ���ʡ�10000(���磺3456��Ӧ��34.56%)
	"sysCpuRate": 3456,		// ϵͳCPUʹ���ʡ�10000(���磺3456��Ӧ��34.56%)
	"rtt": 10,				// ����ʱ�ӣ�Round-Trip Time������λ����;
	
	"videoEncodeParams": [	// ��Ƶ�������
		{
			"viewType": 0,	// �������ͣ���Ϊ������Ϣ������0-��·���� 2-��·
			"width": 0,		// ��Ƶ�����
			"height": 0,	// ��Ƶ�����
			"fps": 0,		// ��Ƶ����ʵʱ֡�ʡ�10
			"angle": 253,	// �Ƕ�
			"bitrate": 0	// ��Ƶ��������(�ް�ͷ)
		},
		{
			"viewType": 0,
			"width": 0,
			"height": 0,
			"fps": 0,
			"angle": 253,
			"bitrate": 0
		},
		{
			"viewType": 2,
			"width": 1920,
			"height": 1080,
			"fps": 0,
			"angle": 0,
			"bitrate": 0
		}
	],
	"videoDecodeParams": [		// ��Ƶ�������
		{
			"userId": "userId",	// �����û�
			"viewType": 0,		// �������ͣ���Ϊ������Ϣ������0-��·���� 2-��·
			"width": 1280,		// ��Ƶ�����
			"height": 720,		// ��Ƶ�����
			"fps": 131,			// ��Ƶ�������֡�ʡ�10
			"bitrate": 193		// ��Ƶ�����������(�ް�ͷ)
		}
	],
	
	"videoMainQosParam": {		// ��·��Ƶ�����·�����
		"bitrate": 0,	// ����
		"fps": 0,		// ֡��
		"height": 0,	// ��Ƶ��
		"width": 0		// ��Ƶ��
	},
	"videoAuxQosParam": {		// ��·��Ƶ�����·�����
		"bitrate": 0,	// ����
		"fps": 0,		// ֡��
		"height": 0,	// ��Ƶ��
		"width": 0		// ��Ƶ��
	},
	
	"audioEncodeParams": {		// ��Ƶ�������(�˲�����ʱΪ�գ�����������)
		"encodeBitrate": 0	//��Ƶ��������
	},
	"audioDecodeParams": [		// ��Ƶ�������(�˲�����ʱΪ�գ�����������)
		{
			"userId": "UserId",	// ��Ƶ�����û�
			"sampleRate": 48000,// ��Ƶ���������
			"channelCount": 2	// ͨ������1��ʾ������(mono)��2��ʾ������(stereo)
		}
	],
	
	"audioQosParam": {			// ��Ƶ�����·�����
		"aecEnable": 1,		// AEC�����Ƿ���
		"agcEnable": 0,		// AGC�����Ƿ���
		"bitrate": 24000,	// ����
		"channelCount": 2,	// ͨ������1��ʾ������(mono)��2��ʾ������(stereo)
		"sampleRate": 48000 // ������
	}
}
```