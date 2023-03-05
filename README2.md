https://github.com/google-research/google-research/tree/master/tabnet


multi_task_example.ipynb
    clf = TabNetMultiTaskClassifier()
    clf.fit()

abstract_model.py
    fit()

        _construct_loaders(X_train, y_train, eval_set)
            train_dataloader, valid_dataloaders = create_dataloaders()
                train_dataloader = DataLoader()

        _train_epoch()
            _train_batch()
