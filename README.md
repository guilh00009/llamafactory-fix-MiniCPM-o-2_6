VERSÃO BRASILEIRA DO TUTORIAL

ok eu arrumei muita merda no llamafactory, não me entenda mal, o llamafactory é bom, mas esta claramente desatualizado

tutorial para treinar o minicpm v2.6 omni funcionando atualizado:

1. instale normalmente o llama factory

2 rode isso: ```pip install llamafactory --upgrade```

3. rode isso: ```pip install transformers==4.49.0```

4. substitua o arquivo que esta no cache por este com o mesmo nome: image_processing_minicpmv.py

agora é possivel treinar o modelo sem problemas!

se esta com duvidas sobre onde é localizado, deixei uma print da localização disso no google colab como exemplo!


-----

ENGLISH TUTORIAL VERSION

Okay, I fixed a shitload of crap in LLaMA-Factory. Don’t get me wrong, LLaMA-Factory is good, but it’s clearly outdated as fuck.

Tutorial to train MiniCPM v2.6 Omni without any bullshit:

Install LLaMA-Factory like a normal human.

Run this shit: ```pip install llamafactory --upgrade```

Run this shit too: ```pip install transformers==4.49.0```

Replace the file in the cache with this one using the same damn name: image_processing_minicpmv.py

Now you can train the model without any more fucking problems!

If you’re wondering where the hell it’s located, I left a screenshot of its location in Google Colab as an example!

<img width="443" height="705" alt="Captura de tela 2025-08-22 145355" src="https://github.com/user-attachments/assets/57cfe087-c97c-4ed1-b843-0598ce5d4254" />

(essas são as configs que eu estou para treinar o meu modelo como teste)
This is the configs im using to train my model as a test.
<img width="1784" height="847" alt="Captura de tela 2025-08-22 152935" src="https://github.com/user-attachments/assets/58ecb7dd-32cd-43bb-b7b6-cde595df2f54" />
