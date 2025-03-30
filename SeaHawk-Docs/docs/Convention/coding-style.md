# 📝 코딩 스타일 가이드

## 1. 네이밍 규칙 (Naming Convention)

### 변수명
- **카멜케이스(CamelCase) 사용:** `int missileSpeed;`
- **멤버 변수는 `_` 접미사:** `int mMissileSpeed;`

### 함수명
- **동사 + 명사 형태 사용:** `void LaunchMissile();`

### 상수
- **대문자 + 언더스코어:** `const int MAX_RANGE = 1000;`

## 2. 코드 인덴트 (Indentation)
- **공백 4칸 대신 탭 사용**
- `{}` 블록은 항상 개행 후 사용  

```cpp
if (isReady) 
{
	FireMissile();
}
```

## 3. 주석 스타일
- 한 줄 주석: // 사용
- 여러 줄 주석: /**/ 사용

```cpp
/**
 * @brief 미사일을 발사하는 함수
 * @param target 좌표
 */
void FireMissile(Coordinates target);
```

## 4. 파일명 및 디렉터리 구조
- 파일명: PascalCase 사용 (MissileControl.cpp)
- 헤더 파일: .h 확장자 사용 (MissileControl.h)

