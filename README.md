import random

# Definindo as emoções e sentimentos
emocoes = ['encantado', 'apaixonado', 'feliz', 'nervoso', 'raivoso']
sentimentos = ['amor', 'desejo', 'alegria', 'preocupação', 'raiva']

# Selecionando as emoções e sentimentos de forma aleatória
emocao_brad = random.choice(emocoes)
sentimento_brad = random.choice(sentimentos)

emocao_angelina = random.choice(emocoes)
sentimento_angelina = random.choice(sentimentos)

# Interação inicial
print("Brad está", emocao_brad, "e sente", sentimento_brad)
print("Angelina está", emocao_angelina, "e sente", sentimento_angelina)

# Brad expressa raiva
print("Brad: Angelina, você está me deixando furioso!")
print("Angelina: Desculpe, não era minha intenção.")

# Atualizando emoção de Brad e sentimento de Angelina
emocao_brad = 'raivoso'
sentimento_angelina = 'culpa'

# Exibindo alterações
print("Brad agora está", emocao_brad)
print("Angelina agora sente", sentimento_angelina)
