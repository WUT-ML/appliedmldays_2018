# appliedmldays_2018
Workshop: Discovering Brain Structure with Machine Learning, edycja politechniczna

## Plan
1. Wprowadzenie - dr Tomasz Trzciński
2. Neuronauka obliczeniowa
    * Dlaczego nie pracujemy na danych z mózgu człowieka?
    * Dlaczego pracuje się na danych zwierzęcych?
    * Rodzaje obrazowania (światło vs. elektroda)
2. Obrazowanie mózgu zebrafish
3. Dane
    * Struktura 3D, 4D
    * Rozmiar danych, typ
    * Co dane z obrazowania właściwie prezentują?
    * Pomysły na analizy.
4. PCA
    * intuicja
    * implementacja
    * interpretacja ([artykuł 1](http://www.cell.com/neuron/pdf/S0896-6273(14)00050-6.pdf), [artykuł 2](https://elifesciences.org/articles/12741))
5. Podsumowanie
    * interakcje biologii z machine learning

## setup
```bash
git clone https://github.com/WUT-ML/appliedmldays_2018.git
virtualenv workshop -p python3.5
source workshop/bin/activate
pip3 install -r requirements.txt
```
Advanced users may want to install [Fiji](https://fiji.sc/#download), that is image processing package implemented in Java.


## materials (raw)
### biology
1. [Whole-brain functional imaging at cellular level](https://www.youtube.com/watch?v=EJo-0UxJ7P0), video
2. [Whole-brain functional imaging at cellular resolution using light-sheet microscopy](https://www.janelia.org/sites/default/files/Library/Ahrens%202013_4.pdf)
3. [Ultrasensitive fluorescent proteins for imaging neuronal activity](https://www.janelia.org/sites/default/files/Library/nature12354.pdf) (fig. 3a)
4. [Fictive swimming the light-sheet virtual reality setup](https://elifesciences.org/articles/12741#media2)
5. [Visualizations of the brain activity](https://www.janelia.org/sites/default/files/Labs/Keller%20Lab/Keller%202014.pdf) fig. 2

### PCA
1. [data-points cloud](http://resources.sttrcancer.org/style/toolImages/pca.png)
2. [intuition](https://media.springernature.com/full/nature-static/assets/v1/image-assets/nbt0308-303-F1.gif)
3. [sklearn PCA object](http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html#sklearn.decomposition.PCA)

### might be useful
1. [z-score](https://docs.scipy.org/doc/scipy-0.18.1/reference/generated/scipy.stats.zscore.html)
2. [scikit-image module io](http://scikit-image.org/docs/stable/api/skimage.io.html)
