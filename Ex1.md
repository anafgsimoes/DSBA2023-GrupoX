# DSBA2023-GrupoX
#Exercicio1 
T1 = input('Introduz a nota do teu primeiro teste: ')
T1 = eval(T1)
T2 = input('Introduz a nota do teu segundo teste ')
T2 = eval(T2)
t1 = input('Introduz a nota do teu primeiro trabalho: ')
t1 = eval(t1)
t2 = input('Introduz a nota do teu segundo melhor trabalho: ')
t2 = eval(t2)
t3 = input('Introduz a nota do teu terceiro trabalho:')
t3 = eval(t3)
trabalhos= [t1,t2,t3]
trabalhos.sort(reverse=True)
print (trabalhos)

Nota=T1*0.4+T2*0.2+trabalhos[0]*0.2+trabalhos[1]*0.15+trabalhos[2]*0.05
print(f'A nota final é:{Nota}')
