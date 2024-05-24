ollama link: curl -fsSL https://ollama.com/install.sh | sh
configurar server: ollama serv
activacion de ollama: ollama pull tinyllama
tipo de ollama: ollama run tinyllama   (Forma generativa)
modo chat: ollama run tinyllama
modo code: ollama run tinyllama + (Lo que quieres preguntar)

code= curl http://localhost:11434/api/generate -d '{
  "model": "tinyllama",
  "prompt":"¿Por que el cielo es azul?",
}'

code= curl http://localhost:11434/api/generate -d '{
  "model": "tinyllama",
  "prompt":"¿Por que el cielo es azul?",
  "stream": false
}'
