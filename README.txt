Part A
1a:
    best k = 11, test_acc = 68.42%
    for k = [1,6,11,16,21,26]
    valid_acc = [0.62447, 0.67809, 0.68952, 0.67555, 0.6692, 0.65227]
1b+c:
    Item method
    1
    Accuracy: 0.607112616426757
    6
    Accuracy: 0.6542478125882021
    11
    Accuracy: 0.6826136042901496
    16
    Accuracy: 0.6860005644933672
    21
    Accuracy: 0.6922099915325995
    26
    Accuracy: 0.69037538808919
    Best k:  21
    Validation-
    Accuracy: 0.6922099915325995
    Test-
    Accuracy: 0.6816257408975445

d: user-based is better because it has a higher test accuracy (out of domain
generalization),and a lower k value, which means it is less computationally expensive.

e:
- we haven't used the meta data yet, which may present useful patterns.
We can't also assume two students of the same brain.
- similar question_id doesn't mean similar topics


2
