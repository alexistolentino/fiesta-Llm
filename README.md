# fiesta-Llm
## 1. Instalacion de ollama
'''
curl -fsSL https://ollama.com/install.sh | sh'''

## 2. Arrancar el servidor
'''
ollama serve'''

## 3. Descargar un modelo
'''
ollama pull tinyllama'''

## 4. Correr el modelo tinyllama
'''
ollama run tinyllama'''

## 5. entrar en modo chat 

ollama run tinyllama' y enter
## 6. mostrar los procesos que has hecho
ps -a
## 7. consumir una api 
curl http://127.0.0.1:11434/api/generate -d'{
  "model": "tinyllama",
  "prompt":"porque el cielo es azul?",
"stream": false
}'
