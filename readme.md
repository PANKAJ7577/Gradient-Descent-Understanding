# Gradient Descent Algorithm

Gradient descent (GD) is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function. This method is commonly used in machine learning (ML) and deep learning(DL) to minimise a cost/loss function (e.g. in a linear regression).

![1) best fit line](https://user-images.githubusercontent.com/37456341/158859589-be43fcb1-e0cf-4051-a108-42e0b49256e4.gif)

![2) gd algo](https://user-images.githubusercontent.com/37456341/158860140-67475a8d-fe71-44aa-a2be-c7bb082e20ab.gif)

![4) b vs epochs](https://user-images.githubusercontent.com/37456341/158860330-b6a53045-e61a-454c-9189-2936f9f3ffd1.gif)

![5) m vs epochs](https://user-images.githubusercontent.com/37456341/158860269-978b3988-bf44-4960-904f-5b283c130c8d.gif)

![6) contour plot](https://user-images.githubusercontent.com/37456341/158860386-c51c9f0f-30f6-4724-b8f2-cc2caaef974c.gif)

## Effect of learning rate on Gradient Descent Algorithm

Gradident Descent algorithm is very sensitive to thr learning rate

### Following are the three possible effects:
1) Best learning rate: Here the algorithm converges within the defined epochs
![7) best learning rate](https://user-images.githubusercontent.com/37456341/158860410-b9049548-de84-4eff-a961-1d8a4f32ed58.gif)


2) Low learning rate: Here the steps are going to be very small, hence the convergence might not take place within the defined epochs.
![8) low learning rate](https://user-images.githubusercontent.com/37456341/158860454-6322b1e7-83e6-40f6-a87f-aae7cea7ce37.gif)

3) High learning rate: In this case the algorithm may never converge to the minima.
![9) high learning rate](https://user-images.githubusercontent.com/37456341/158859758-82f9f9e4-ed02-4e7b-906d-53ff9bd939d4.gif)

![3) cost function](https://user-images.githubusercontent.com/37456341/158860221-5ad2743a-cc6b-4370-a92a-955d97e39f83.gif)
