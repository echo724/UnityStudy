# Unity LifeCycle
```C#
public class LifeCycle: Monobehaviour{
    void Awake(){
    }
    void Start(){
    }
    void FixedUpdate(){
    }
    void Update(){}

    void LateUpdate(){}
}
```

## 초기화, Initialization
### Awake()
- 가장 먼저 실행
- 한 번만 실행

### Start()
- 업데이트 시작 직전, 최초 실행
- 한 번만 실행

## Physics, 물리

###  FixedUpdate()
- 물리 연산 업데이트
- 여러 번
- 고정된 실행 주기로 CPU 많이 사용

## Game Logic

### Update()
- 게임 로직 업데이트
- 주기적으로 변하는 로직을 넣을떄 사용
- 환경에 따라 실행주기 바뀜

### LateUpdate()
- 마지막에 실행
- 모든 업데이트 실행 후에 실행됨
- 카메라, 후처리 등등

## 해체

### OnDestroy()
- 게임 오브젝트가 삭제될 때

## 활성화

### OnEnable()
- 게임 오브젝트가 활성화 되었을 때
- Awake와 Start 사이

## 비활성화

### OnDisable()
- 게임 오브젝트 비활성화

