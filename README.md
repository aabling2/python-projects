# Garimpa Emprego

Script de busca aprofundada de empregos em sites que não surgem como primeiras opções nas buscas do google. Utilizando web scraping das páginas recolhidas com uso de palavras-chave de ligação com o currículo, habilidades e preferências do indivíduo para definir as prioridades de busca.

# Instalar

pip install google

pip install beautifulsoup4

# Observações

**search(query, tld='com', lang='en', num=10, start=0, stop=None, pause=2.0)**

query : query string that we want to search for.

tld : tld stands for top level domain which means we want to search our result on google.com or google.in or some other domain.

lang : lang stands for language.

num : Number of results we want.

start : First result to retrieve.

stop : Last result to retrieve. Use None to keep searching forever.

pause : Lapse to wait between HTTP requests. Lapse too short may cause Google to block your IP. Keeping significant lapse will make your program slow but its safe and better option.

Return : Generator (iterator) that yields found URLs. If the stop parameter is None the iterator will loop forever.
