# Video clip preprocessing
I created a method that extracts clip from a video based on moment. This code is probably not up to date and might need some adjustment. A refined version of this algorithm was used in my Thesis to extract action sequences in videos. The algorithm has as parameters:
- Clip size defined in number of frames.
- A minimum number of correlated frames, based on their visual similarities (this value must be less than the clip size). More correlated frames are expected, less sequences will be extracted.
- A threshold value for the visual similarity.

This algorithm was used to extract violence sequences from videos, but it should work also on any general video.
