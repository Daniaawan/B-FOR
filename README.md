# B-FOR: Background-Free Objectness Learning for Class-Agnostic Detection

Official implementation of **"Background-Free Objectness Learning for Class-Agnostic Detection"** (BMVC 2026).

Under incomplete annotation, standard detectors treat every unlabeled region as background during training, tying objectness to the training taxonomy rather than to generic object structure. B-FOR removes this assumption: it learns class-agnostic objectness by predicting dense multi-scale object-center and displacement-aware scale fields, with supervision confined to reliably annotated regions rather than penalizing everything outside them as negative. Objects emerge as local maxima in the learned field and are decoded into boxes using the corresponding scale field.

Trained entirely from scratch (no ImageNet pretraining, ~31M parameters), B-FOR generalizes to unseen categories and cross-dataset distributions on PASCAL VOC, COCO, Open Images, and LVIS.


CODE COMING SOON
