# Eksperymenty z Sparse Autoencoderami

Jest to mój najnowszy projekt, który dopiero zacząłem. Myślę, że rozwinę go w przyszłości i napiszę na ten temat pracę magisterską.

Skrypt jest napisany w Pythonie z wykorzystaniem biblioteki `torch`.

Badam w nim, czy Sparse Autoencodery są w stanie wyuczyć się interpretowalnych reprezentacji. Jak dotąd zaimplementowałem trzy metody:
- Klasyczny SAE z top-k  
- Eksperymentalna metoda opierająca się na analizie rozkładu aktywacji  
- Metoda łącząca top-k z selekcją aktualnie najsłabszych reprezentacji  

Kod jest nadal w fazie rozwoju, dlatego zawiera wiele wykresów i nie ma jeszcze uporządkowanej struktury. Mimo to uważam, że dobrze odzwierciedla on mój aktualny poziom umiejętności.
