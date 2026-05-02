## Training Dynamics

The model exhibits stable convergence, with a consistent decrease in training loss and a steady increase in validation mIoU.

The absence of strong oscillations in the validation curve suggests good generalization, despite the class imbalance inherent to the task.

![mIoU Curve](assets/val_mIoU.svg)
![Loss Curve](assets/train_loss.svg)

## Minority Class Performance (Mining)

Mining regions represent a small fraction of the total pixels, making the task highly imbalanced.

To evaluate performance beyond aggregate metrics, we analyze IoU for the mining class specifically.

The model achieves strong localization performance, indicating that it effectively captures subtle spectral and temporal changes associated with mining activity.

![IoU Mining](assets/val_IoU_1.svg)
