#include "Map.h"
#include <iostream>
#include <Windows.h>

MCI_OPEN_PARMS m_mciOpenParms;
MCI_PLAY_PARMS m_mciPlayParms;
DWORD m_dwDeviceID;
MCI_OPEN_PARMS mciOpen;
MCI_PLAY_PARMS mciPlay;
void Ending(int Hong) {
	char z = 0;
	int i = 0;
	system("cls");
	gotoxy(104, 8);
	printf("========================================");
	gotoxy(104, 19);
	printf("========================================");
	if (Hong == 1) {
		char str0[] = "나는 무사히 집에 도착할 수 있었다..";
		for (i = 0; str0[i]; i++) {
			gotoxy(8 + i * 2, 8);
			printf("%c", str0[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		char str1[] = "홍길동..그 녀석을";
		for (i = 0; str1[i]; i++) {
			gotoxy(8 + i * 2, 10);
			printf("%c", str1[i]);
			Sleep(70);
		}
		do {
			gotoxy(110, 13);
			printf("1. 용서할 수 없었다");
			gotoxy(110, 15);
			printf("2. 용서해 주었다.");
			z = _getch();
		} while (z != '1' && z != '2');
		gotoxy(110, 13);
		printf("                     ");
		gotoxy(110, 15);
		printf("                     ");
		if (z == '1') {
			char str2[] = "홍길동..그 녀석을 용서할 수 없었다.";
			for (i = 0; str2[i]; i++) {
				gotoxy(8 + i * 2, 10);
				printf("%c", str2[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
			char str3[] = "나는 당장 교수님께 말씀드렸더니";
			for (i = 0; str3[i]; i++) {
				gotoxy(8 + i * 2, 12);
				printf("%c", str3[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
			char str4[] = "홍길동은 시험자격을 박탈당했다..";
			for (i = 0; str4[i]; i++) {
				gotoxy(8 + i * 2, 14);
				printf("%c", str4[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
			char str5[] = "그녀석은 결국 자퇴를 했다고한다..";
			for (i = 0; str5[i]; i++) {
				gotoxy(8 + i * 2, 16);
				printf("%c", str5[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
		}
		if (z == '2') {
			char str6[] = "홍길동..그 녀석을 용서해 주었다.";
			for (i = 0; str6[i]; i++) {
				gotoxy(8 + i * 2, 10);
				printf("%c", str6[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
			char str7[] = "일을 크게 벌리고 싶지 않았고 ,";
			for (i = 0; str7[i]; i++) {
				gotoxy(8 + i * 2, 12);
				printf("%c", str7[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
			char str8[] = "무엇보다 홍길동이랑 엮이고 싶지않았다..";
			for (i = 0; str8[i]; i++) {
				gotoxy(8 + i * 2, 14);
				printf("%c", str8[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
			char str88[] = "피곤하다..얼른 자자";
			for (i = 0; str88[i]; i++) {
				gotoxy(8 + i * 2, 16);
				printf("%c", str88[i]);
				Sleep(70);
			}
			do {
				z = _getch();
			} while (z != 0x7A);
		}
		char str99[] = "~ TRUE엔딩 ~";
		for (i = 0; str99[i]; i++) {
			gotoxy(8 + i * 2, 18);
			printf("%c", str99[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		system("cls");

	}
	else if (Hong == 0) {
		char str9[] = "나는 재빨리 건물에서 탈출했다.";
		for (i = 0; str9[i]; i++) {
			gotoxy(8 + i * 2, 8);
			printf("%c", str9[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		char str10[] = "무언가 찜찜한 구석이 있지만...";
		for (i = 0; str10[i]; i++) {
			gotoxy(8 + i * 2, 10);
			printf("%c", str10[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		char str11[] = "으으..그만 생각하자 탈출했으니 된거야!";
		for (i = 0; str11[i]; i++) {
			gotoxy(8 + i * 2, 12);
			printf("%c", str11[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		char str12[] = "얼른 가서 시험공부나 하자!!!";
		for (i = 0; str12[i]; i++) {
			gotoxy(8 + i * 2, 14);
			printf("%c", str12[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		char str13[] = "~ NORMAL엔딩 ~";
		for (i = 0; str13[i]; i++) {
			gotoxy(8 + i * 2, 16);
			printf("%c", str13[i]);
			Sleep(70);
		}
		do {
			z = _getch();
		} while (z != 0x7A);
		system("cls");
	}
}

void printcard() {
	gotoxy(20, 5);
	printf("          ----------카드키 사용 내역----------");
	gotoxy(20, 7);
	printf("                            ::                   ");
	gotoxy(20, 8);
	printf("                            ::                   ");
	gotoxy(20, 10);
	printf("        (퇴실)  이 영 희    ||    10 : 01 : 56  ");
	gotoxy(20, 12);
	printf("        (퇴실)  김 철 수    ||    10 : 02 : 14  ");
	gotoxy(20, 14);
	printf("        (입실)  홍 길 동    ||    11 : 26 : 30  ");
}
void images(int x, int y, int num)
{
	HINSTANCE hInstance = GetModuleHandle(NULL);
	HWND myconsole = GetConsoleWindow();
	HBITMAP hImage, hOldBitmap;
	hImage = 0;
	HDC hdc = GetDC(myconsole);
	HDC hMemDC = CreateCompatibleDC(hdc);

	switch (num) {
	case 0:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("main.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	case 1:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("text.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	case 2:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("4.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	case 3:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("3.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	case 4:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("how.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	case 5:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("hint.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	case 6:
		hImage = (HBITMAP)LoadImage(NULL,
			TEXT("over.bmp"),
			IMAGE_BITMAP,
			0,
			0,
			LR_LOADFROMFILE | LR_CREATEDIBSECTION);
		break;
	}


	// 이미지 출력 부분
	hOldBitmap = (HBITMAP)SelectObject(hMemDC, hImage);
	BitBlt(hdc, x, y, 1000000, 500000, hMemDC, 0, 0, SRCCOPY);

	return;
}
void How() {
	char z = 0;
	int i;

	char str0[] = "   ";
	for (i = 0; str0[i]; i++) {
		gotoxy(8 + i * 2, 13);
		printf("%c", str0[i]);
		Sleep(100);
	}
	images(0, 0, 4);
	images(0, 0, 4);
	Sleep(1000);
	char str[] = "당신은 학교에 갇혀버렸습니다 .";
	for (i = 0; str[i]; i++) {
		if (i > 7 && i < 13) {
			color(12);
		}
		gotoxy(8 + i * 2, 8);
		printf("%c", str[i]);
		color(15);
		Sleep(70);
	}
	Sleep(500);
	char str1[] = "아침 8시가 되기 전까지 어서 탈출해야합니다 !";
	for (i = 0; str1[i]; i++) {
		if (i > -1 && i < 11) {
			color(12);
		}
		gotoxy(8 + i * 2, 11);
		printf("%c", str1[i]);
		color(15);
		Sleep(70);
	}
	Sleep(500);

	char str2[] = "주위의 사물을 상호작용 (z키)하여 아이템을 얻으세요 !";
	for (i = 0; str2[i]; i++) {
		if (i > 14 && i < 34) {
			color(12);
		}
		gotoxy(8 + i * 2, 14);
		printf("%c", str2[i]);
		Sleep(70);
		color(15);
	}
	Sleep(500);
	char str3[] = "그럼 행운을 빌어요 ! ! !";
	for (i = 0; str3[i]; i++) {
		if (i > 4 && i < 11) {
			color(12);
		}
		gotoxy(8 + i * 2, 17);
		printf("%c", str3[i]);
		Sleep(70);
		color(15);
	}
	Sleep(500);
	char str4[] = "z키를 누르면 시작합니다.";
	for (i = 0; str4[i]; i++) {
		color(12);
		gotoxy(30 + i * 2, 23);
		printf("%c", str4[i]);
		Sleep(70);
	}
	color(15);
	do {
		z = _getch();
	} while (z != 0x7A);
}
void gotoxy(int x, int y) {
	COORD Pos = { x , y };
	SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), Pos);
}
void color(unsigned short color)
{
	HANDLE hCon = GetStdHandle(STD_OUTPUT_HANDLE);
	SetConsoleTextAttribute(hCon, color);
}
void Play_BGM(int dwID) {
	mciOpen.lpstrElementName = "BGM.mp3";
	mciOpen.lpstrDeviceType = "mpegvideo";

	mciSendCommand(NULL, MCI_OPEN, MCI_OPEN_ELEMENT | MCI_OPEN_TYPE,
		(DWORD)(LPVOID)&mciOpen);

	dwID = mciOpen.wDeviceID;

	mciSendCommand(dwID, MCI_PLAY, MCI_DGV_PLAY_REPEAT, // play & repeat
		(DWORD)(LPVOID)&m_mciPlayParms);
}

void prolog() {
	system("cls");
	char z = 0;
	do {
		z = _getch();
		gotoxy(10, 5);
		printf("========================================================");
		gotoxy(20, 10);
		printf("으음...끙..추워어..훌쩍");
		gotoxy(10, 15);
		printf("========================================================");
	} while (z != 0x7A);
	do {
		gotoxy(10, 5);
		printf("========================================================");
		gotoxy(20, 10);
		printf("으음.............                 ");
		gotoxy(10, 15);
		printf("========================================================");
		z = _getch();
	} while (z != 0x7A);
	do {
		for (int i = 0; i < 5; i++) {
			gotoxy(10, 5);
			printf("=======================================================");
			gotoxy(20 + 2 * (i % 2), 10);
			printf("  헉?! 뭐야!!! 나 언제 잠들었지?   ");
			gotoxy(10, 15);
			printf("======================================================");
			Sleep(100);
		}
		z = _getch();
	} while (z != 0x7A);
	do {
		z = _getch();
		gotoxy(10, 5);
		printf("========================================================");
		gotoxy(20, 10);
		printf("일단 너무 어둡다...불 부터 켜야겠다");
		gotoxy(10, 15);
		printf("========================================================");
	} while (z != 0x7A);
	system("cls");
}

void Print_interface(Item item)
{
	gotoxy(104, 1);
	printf("모은 쪽지 : %d ", item.note);

	gotoxy(101, 23);
	printf("------아이템-------------------------------");
	gotoxy(101, 29);
	printf("-------------------------------------------");

	if (item.class_key == 1 && item.overlap == 0)
	{
		gotoxy(112, 26);
		printf("  교실카드키");
	}
	if (item.eel == 1 && item.overlap == 0) {
		gotoxy(101, 26);
		printf("  건전지");
	}
	if (item.eel == 2) {
		gotoxy(101, 26);
		printf("        ");
	}
	if (item.class_ps == 1 && item.overlap == 0)
	{
		gotoxy(130, 26);
		printf("1214");
	}

	if (item.hall_key == 1)
	{
		gotoxy(101, 26);
		printf("  복도카드키");
	}

	if (item.bath_key == 1)
	{
		if (item.hall_key != 1)
		{
			gotoxy(101, 26);
			printf("  의문의열쇠");
		}
		if (item.hall_key == 1)
		{
			printf("  의문의열쇠");
		}
	}

	if (item.Clear_key == 1)
	{
		gotoxy(101, 26);
		printf("  현관 카드키");
	}
}

void setcursortype(CURSOR_TYPE c)                                 //커서제거함수 내용
{
	CONSOLE_CURSOR_INFO CurInfo;                                  //커서제거함수 내용
	switch (c)                                                     //커서제거함수 내용
	{
	case NOCURSOR:                                                   //커서제거함수 내용
		CurInfo.dwSize = 1;                                         //커서제거함수 내용
		CurInfo.bVisible = FALSE;                                      //커서제거함수 내용
		break;                                                         //커서제거함수     aaaa
	case SOLIDCURSOR:                                                    //커서제거함수 내용
		CurInfo.dwSize = 100;                                          //커서제거함수 내용
		CurInfo.bVisible = TRUE;                                        //커서제거함수 내용
		break;                                                           //커서제거함수 내용
	case NORMALCURSOR:                                                      //커서제거함수 내용
		CurInfo.dwSize = 20;                                                 //커서제거함수 내용
		CurInfo.bVisible = TRUE;                                             //커서제거함수 내용
		break;                                                                 //커서제거함수 내용
	}
	SetConsoleCursorInfo(GetStdHandle(STD_OUTPUT_HANDLE), &CurInfo);            //커서제거함수 내용
}

void Draw_door(char map[][100])
{
	for (int i = 0; i < 30; i++) {
		for (int j = 0; j < 100; j++) {
			char temp = map[i][j];
			switch (temp) {
			case '0':
				printf("  ");
				break;
			case '1':
				printf("━ ");
				break;
			case '2':
				printf("┃ ");
				break;
			case '3':
				printf("┏ ");
				break;
			case '4':
				printf("┓ ");
				break;
			case '5':
				printf("┛ ");
				break;
			case '6':
				printf("┗ ");
				break;
			case '7':
				printf("▨");
				break;
			case '8':
				printf("▧");
				break;
			case '9':
				printf("▒");
				break;
			case 'a':
				printf("①");
				break;
			case 'b':
				printf("②");
				break;
			case 'c':
				printf("③");
				break;
			case 'd':
				printf("④");
				break;
			case 'e':
				printf("⑤");
				break;
			case 'f':
				printf("⑥");
				break;
			case 'g':
				printf("⑦");
				break;
			case 'h':
				printf("⑧");
				break;
			case 'i':
				printf("⑨");
				break;
			case 'j':
				printf("ⓞ");
				break;
			case 'k':
				printf("＃");
				break;
			case 'p':
				printf("★");
				break;
			case 'x':
				printf("●");
				break;
			case 'y':
				printf("▲");
				break;
			case '=':
				printf("=");
				break;
			}
		}
		puts("");
	}
	gotoxy(45, 4);
	printf("door lock");
	gotoxy(45, 17);
	printf("〈CBNU〉");
	gotoxy(47, 23);
	printf("CARD");
}
void Draw_bathroom(char map[][100])
{
	for (int i = 0; i < 30; i++) {
		for (int j = 0; j < 100; j++) {
			char temp = map[i][j];
			switch (temp) {
			case '0':
				printf("  ");
				break;
			case '1':
				printf("━ ");
				break;
			case '2':
				printf("┃ ");
				break;
			case '3':
				printf("┏ ");
				break;
			case '4':
				printf("┓ ");
				break;
			case '5':
				printf("┛ ");
				break;
			case '6':
				printf("┗ ");
				break;
			case '7':
				printf("▨");
				break;
			case '8':
				printf("▧");
				break;
			case '9':
				printf("▒");
				break;
			case'a':
				printf("〓");
				break;
			case 'b':
				printf("┣ ");
				break;
			case'c':
				printf("┳ ");
				break;
			case'd':
				printf("┫");
				break;
			case'e':
				printf("┻ ");
				break;
			case'f':
				printf("▣");
				break;
			case'g':
				printf("■");
				break;
			case 'D':
				printf("【");
				break;
			case'=':
				printf("=");
				break;
			case 'K':
				printf("▣");
				break;
			}
		}
		puts("");
	}
}
void Draw_hall(char map[][100])
{
	for (int i = 1; i < 30; i++) {
		gotoxy(1, i);
		for (int j = 0; j < 100; j++) {
			char temp = map[i][j];
			switch (temp) {
			case '0':
				printf("  ");   break;
			case '1':
				printf("━ ");   break;
			case '2':
				printf("┃ ");   break;
			case '3':
				printf("┏ ");   break;
			case '4':
				printf("┓ ");   break;
			case '5':
				printf("┛ ");   break;
			case '6':
				printf("┗ ");   break;
			case '7':
				printf("==");   break;
			case '8':
				printf("▨");   break;
			case '9':
				printf("▣");   break;
			case 'a':
				color(6 * 16 + 0);
				printf("●");
				color(15);
				break;
			case 'b':
				printf("┃ ");   break;
			case 'c':
				printf("※");   break;
			case 'd':
				printf("┏┓");   break;
			case 'e':
				printf("┫ ");   break;
			case 'f':
				printf("┣ ");   break;
			case 'g':
				printf("■");   break;
			case 'h':
				printf("┗┛");   break;
			case 'i':
				printf("┃┃");   break;
			case 'j': {
				color(11);
				printf("＠");
				color(15);
				break;
			}
			case 'k':
				color(6 * 16 + 0);
				printf("●");
				color(15);
				break;
			case '=':
				printf("="); break;
			case 'p':
				printf("  "); break;
			case 'q':
				printf("  "); break;
			case 'C':
				printf("=="); break;
			case 'G':
				printf("  "); break;
			case 'F':
				printf("  "); break;
			case 'D':
				printf("】"); break;
			case 'O':
				printf("=="); break;
			case 'R':
				printf("=="); break;
			case 'X':
				printf("  "); break;
			case 'Y':
				printf("  "); break;
			case'H':
				printf("●");
				break;
			case'B':
				printf("▲");
				break;
			}
		}
		puts("");
	}
}
void Draw_classroom(char map[][100], int h, int w)
{
	int i, j;
	for (i = 0; i < h; i++)
	{
		for (j = 0; j < w; j++)
		{
			char temp = map[i][j];

			switch (temp)
			{
			case '0':
				printf("  ");
				break;
			case '1':
				printf("■");
				break;
			case '2':
				printf("▧");
				break;
			case '3':
				printf("▤");
				break;
			case '4':
				printf("【");
				break;
			case '5':
				printf("─ ");
				break;
			case '6':
				printf("=");
				break;
			case 'x':
				printf("●");
				break;
			case 'y':
				printf("▲");
				break;
			case'K':
				printf("▤");
				break;
			case'C':
				color(9);
				printf("▤");
				color(15);
				break;
			case'A':
				printf("▤");
				break;
			case'B':
				printf("▤");
				break;
			case'S':
				printf("  ");
				break;
			default:
				break;
			}
		}
		puts("");
	}
}

void Draw_officeroom(char map[][100])
{
	for (int i = 0; i < 30; i++) {
		for (int j = 0; j < 100; j++) {
			char temp = map[i][j];
			switch (temp) {
			case '0':
				printf("  ");
				break;
			case '1':
				printf("━ ");
				break;
			case '2':
				printf("┃ ");
				break;
			case '3':
				printf("┏ ");
				break;
			case '4':
				printf("┓ ");
				break;
			case '5':
				printf("┛ ");
				break;
			case '6':
				printf("┗ ");
				break;
			case '7':
				printf("▨");
				break;
			case '8':
				printf("▧");
				break;
			case '9':
				printf("▒");
				break;
			case'a':
				printf("〓");
				break;
			case 'b':
				printf("┣ ");
				break;
			case'c':
				printf("┳ ");
				break;
			case'd':
				printf("┫ ");
				break;
			case'e':
				printf("┻ ");
				break;
			case'f':
				printf("▣");
				break;
			case'g':
				printf("■");
				break;
			case 'h':
				printf("》");
				break;
			case'i':
				printf("【");
				break;
			case'j':
				printf("▩");
				break;
			case'k':
				printf("▦");
				break;
			case '=':
				printf("=");
				break;
			case 'A':
				printf("━ ");
				break;
			case 'B':
				printf("━ ");
				break;
			}
		}
		puts("");
	}
}
void Draw_club(char map[][100])
{
	for (int i = 0; i < 30; i++) {
		for (int j = 0; j < 100; j++) {
			char temp = map[i][j];
			switch (temp) {
			case '0':
				printf("  ");
				break;
			case '1':
				printf("━ ");
				break;
			case '2':
				printf("┃ ");
				break;
			case '3':
				printf("┏ ");
				break;
			case '4':
				printf("┓ ");
				break;
			case '5':
				printf("┛ ");
				break;
			case '6':
				printf("┗ ");
				break;
			case '7':
				printf("▨");
				break;
			case '8':
				printf("▧");
				break;
			case '9':
				printf("▒");
				break;
			case'a':
				printf("〓");
				break;
			case 'b':
				printf("┣ ");
				break;
			case'c':
				printf("┳ ");
				break;
			case'd':
				printf("┫ ");
				break;
			case'e':
				printf("┻ ");
				break;
			case'f':
				printf("▣");
				break;
			case'g':
				printf("■");
				break;
			case 'h':
				printf("》");
				break;
			case'i':
				printf("【");
				break;
			case'j':
				printf("▩");
				break;
			case'k':
				printf("▦");
				break;
			case'=':
				printf("=");
				break;
			case'O':
				printf("━ ");
				break;
			case'P':
				printf("┃ ");
				break;
			}
		}
		puts("");
	}
}
