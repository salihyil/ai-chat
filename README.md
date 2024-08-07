# Chat-ai

## İçindekiler

- [Genel Bakış](#genel-bakış)
- [Kurulum](#kurulum)
- [Backend](#backend)
  - [Gereksinimler](#backend-gereksinimler)
  - [Kurulum ve Çalıştırma](#backend-kurulum-ve-çalıştırma)
- [Frontend](#frontend)
  - [Gereksinimler](#frontend-gereksinimler)
  - [Kurulum ve Çalıştırma](#frontend-kurulum-ve-çalıştırma)


## Genel Bakış

Kullanıcıların sorularını anında yanıtlayabilir, sohbetler sırasında önerilerde bulunabilir ve çeşitli konularda bilgi sağlayabilir.

## Kurulum

Proje için gerekli ortamı kurmak için aşağıdaki adımları takip edin.

### Backend

#### Backend Gereksinimler

- Node.js
- npm veya yarn, pnpm
- [Ollama indir](https://ollama.com/download)
- [gemma2 modeli indir](https://ollama.com/library/gemma2)

#### Backend Kurulum ve Çalıştırma

1. Depoyu klonlayın:
    ```sh
    git clone https://github.com/salihyil/ai-chat.git
    cd ai-chat/hono-ollama-backend
    ```

2. Gerekli paketleri yükleyin:
    ```sh
    pnpm install
    ```

3. Backend sunucusunu başlatın:
    ```sh
    pnpm dev
    ```

### Frontend

#### Frontend Gereksinimler

- Node.js
- npm veya yarn

#### Frontend Kurulum ve Çalıştırma

1. Depoyu klonlayın (eğer daha önce klonlamadıysanız):
    ```sh
    git clone https://github.com/salihyil/ai-chat.git
    cd ai-chat/react-ollama-frontend
    ```

2. Gerekli paketleri yükleyin:
    ```sh
    pnpm install
    ```

3. Frontend uygulamasını başlatın:
    ```sh
    pnpm dev
    ```
