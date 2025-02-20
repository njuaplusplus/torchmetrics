.. customcarditem::
   :header: Recall At Fixed Precision
   :image: https://pl-flash-data.s3.amazonaws.com/assets/thumbnails/tabular_classification.svg
   :tags: Classification

.. include:: ../links.rst

#########################
Recall At Fixed Precision
#########################

Module Interface
________________

.. autoclass:: torchmetrics.RecallAtFixedPrecision
    :noindex:
    :exclude-members: update, compute
    :special-members: __new__

BinaryRecallAtFixedPrecision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autoclass:: torchmetrics.classification.BinaryRecallAtFixedPrecision
    :noindex:
    :exclude-members: update, compute

MulticlassRecallAtFixedPrecision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autoclass:: torchmetrics.classification.MulticlassRecallAtFixedPrecision
    :noindex:
    :exclude-members: update, compute

MultilabelRecallAtFixedPrecision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autoclass:: torchmetrics.classification.MultilabelRecallAtFixedPrecision
    :noindex:
    :exclude-members: update, compute

Functional Interface
____________________

binary_recall_at_fixed_precision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: torchmetrics.functional.classification.binary_recall_at_fixed_precision
    :noindex:

multiclass_recall_at_fixed_precision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: torchmetrics.functional.classification.multiclass_recall_at_fixed_precision
    :noindex:

multilabel_recall_at_fixed_precision
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. autofunction:: torchmetrics.functional.classification.multilabel_recall_at_fixed_precision
    :noindex:
