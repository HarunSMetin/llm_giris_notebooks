# LLM Giriş Notebook'ları

## Genel Bakış

Bu depo, `gpsandhu23/llm_intro_notebooks`, Büyük Dil Modellerinin (LLM'lerin) çeşitli yönlerini tanıtmak ve keşfetmek için tasarlanmış bir dizi Jupyter notebook'unu içerir. Bu notebook'lar çok çeşitli konuları kapsamaktadır:

- LLM'lere Giriş
- Özetleme Teknikleri
- Sohbet Uygulamaları Oluşturmak
- Retrieval Augmented Generation (RAG)
- Şema Çıkarımı
- LLM'ler için Araçlar
- AI Ajanları Oluşturma

Her notebook bağımsızdır ve LLM'ler hakkında öğrenmeye uygulamalı bir yaklaşım sağlar.

## Kurulum Adımları

Bu notebook'larla başlamak için ortamınızı ayarlamanız gerekecektir:

1. Bu depoyu yerel makinenize klonlayın.
2. `requirements.txt`'te listelenen gerekli bağımlılıkları `pip install -r requirements.txt` komutunu çalıştırarak kurun.
3. Notebook'ları çalıştırmak için Jupyter'in kurulu olduğundan emin olun. Değilse, `pip install jupyter` ile pip'ten kurulabilir.

## Python Sanal Ortamı Ayarlamak

Jupyter notebook'ları çalıştırmak için tutarlı bir ortam sağlamak üzere, bir Python sanal ortamı kullanılması önerilir. Büyük işletim sistemlerinde sanal ortam kurmanın adımları aşağıdadır:

### macOS ve Linux:

1. Terminal açın.
2. Proje dizinine gidin.
3. `python3 -m venv llm_env` çalıştırarak `llm_env` adında bir sanal ortam oluşturun.
4. Sanal ortamı etkinleştirmek için `source llm_env/bin/activate` çalıştırın.

### Windows:

1. Komut İstemini açın.
2. Proje dizinine gidin.
3. `python -m venv llm_env` çalıştırarak `llm_env` adında bir sanal ortam oluşturun.
4. Sanal ortamı etkinleştirmek için `.\llm_env\Scripts\activate` komutunu çalıştırın.

Sanal ortamını devre dışı bırakmak için, terminal veya Komut İsteminde `deactivate` komutunu çalıştırın.

## Ortam Değişkenleri

Bazı notebook'lar, OpenAI, Langchain ve Google API gibi harici hizmetlere erişmek için API anahtarlarına ihtiyaç duyar. Bunları ayarlamak için:

1. `.env_example` dosyasını `.env` adında yeni bir dosyaya kopyalayın.
2. `.env` dosyasını API anahtarlarınızla doldurun.

## API_KEY Linkleri
OPENAI_API_KEY  https://platform.openai.com/api-keys
LANGCHAIN_API_KEY https://smith.langchain.com/ 
ANTHROPIC_API_KEY  https://platform.claude.com/settings/keys
GOOGLE_API_KEY https://aistudio.google.com/app/api-keys

## Katkıda Bulunma

Bu depoya yapılan katkılar hoş karşılanır! İyileştirmeler veya yeni özellikler için öneriniz varsa, bir sorun açmaktan veya bir çekme isteği göndermekten çekinmeyin.
