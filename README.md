# Reconhecimento de fala

## Pré-requisito

No Linux, instale o suporte ao microfone:

```bash
sudo apt install portaudio19-dev
```

## Executar

Dentro da pasta do projeto:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python reconhecimento-fala.py
```

Na primeira execução, o programa pode pedir acesso ao microfone. Para sair do ambiente virtual:

```bash
deactivate
```