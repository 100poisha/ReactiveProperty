# �����[�X�m�[�g

## v2.1.0

### �ǉ�

- ReadOnlyReactiveCollection��ReadOnlyObservableCollection����쐬�ł���悤�ɂ��܂���
	- readOnlyObservableCollectionInstance.ToReadOnlyReactiveCollection(x => CreateViewModel(x))

### �ύX

- ReadOnlyReactiveCollection��Dispose���\�b�h���Ăяo�����Ƃ��ɁA�R���N�V���������̃C���X�^���X�ɑ΂��Ă�Dispose���ĂԂ悤�ɂ��܂���

## v2.0.1

### �ύX

- BooleanNotifier�N���X��INotifyPropertyChanged���������܂����B

## v2.0.0

### �j��I�ύX

- ���O��Ԃ� Codeplex.Reactive ���� Reactive.Bindings �ɕς��܂����B
- ReactiveProperty#ObserveHasError ���\�b�h��ObserveHasErrors�ɕύX���Ă��������B

### �񐄏�

- EventToReactive��񐄏��ɂ��܂����BEventToReactiveProperty��EventToReactiveCommand���g���Ă��������B

### �ύX�_

- ReadOnlyReactiveProperty���v�f���폜����Ƃ���Dispose���\�b�h���ĂԂ悤�ɂȂ�܂����B
- CountNotifier�N���X��INotifyPropertyChanged���������܂����B

### �ǉ�

- Xamarin.Android�p�̋@�\��ǉ����܂���
    - View�N���X��SetBinding�g�����\�b�h��ǉ����܂����B
    - IObservable<T>��SetCommand�g�����\�b�h��ǉ����܂����B
