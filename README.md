# React ile Yapılacaklar Listesi (Todo List)

Bu proje, React kullanarak bir yapılacaklar listesi (Todo List) uygulaması oluşturur.

## Özellikler

- **Görev Ekleme:** Yeni görevler ekleyebilme.
- **Görev Düzenleme:** Var olan görevleri düzenleyebilme.
- **Görev Silme:** Görevleri silebilme.
- **Yerel Depolama:** Görevler yerel depolamada saklanır, böylece sayfa yenilendiğinde görevler kaybolmaz.

## Kurulum

Bu projeyi çalıştırmak için, öncelikle depoyu klonlayın ve bağımlılıkları yükleyin:

```bash
git clone https://github.com/dursuninel/TodoList--React.git
cd TodoList--React
npm install
```

## Kullanım

Projeyi yerel olarak çalıştırmak için aşağıdaki komutu kullanın:

```bash
npm start
```

Bu komut geliştirme sunucusunu başlatacak ve projeyi `http://localhost:3000` adresinde görüntüleyebilirsiniz.

## Canlı Önizleme

Projenin canlı olarak çalışan halini [buradan](https://todolist-drs.netlify.app/) görebilirsiniz.

## Proje Yapısı

```
TodoList--React/
│
├── public/
│   ├── index.html
│
├── src/
│   ├── components/
│   │   ├── EditTodoForm.js
│   │   ├── Todo.js
│   │   ├── TodoForm.js
│   │   ├── TodoWrapper.js
│   │   └── TodoWrapperLocalStorage.js
│   ├── App.css
│   ├── App.js
│   └── index.js
│
└── README.md
```

- **public/**: HTML dosyasını ve diğer genel varlıkları içerir.
- **src/**: React bileşenlerini ve uygulama mantığını içerir.
- **components/**: Uygulamanın bileşenlerini içerir.

## Katkıda Bulunma

Katkılar memnuniyetle karşılanır! Lütfen değişikliklerinizle bir pull request oluşturun.
