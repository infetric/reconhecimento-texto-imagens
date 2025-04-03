# 🖼️ Reconhecimento de Texto em Imagens

Projeto usando OCR (Optical Character Recognition) para extrair texto de imagens.

## 🛠️ Como Usar
1. Coloque imagens na pasta `inputs/`
2. Execute o script Python:
```python
from PIL import Image
import pytesseract

imagem = Image.open('inputs/sua_imagem.jpg')
texto = pytesseract.image_to_string(imagem)
print(texto)
