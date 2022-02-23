## Where to use the file

In my_image_dataset_score.py, line 19 is:

self.attr_score = np.load('/home/chen/work/visual_privacy/vpa/user_studies/attr_score.npy', allow_pickle=True).item()

This file is the required .npy file which is a dictionary containing the attribute score for each user.
