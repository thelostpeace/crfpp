# crfpp
copy from crfpp 0.58 source  

origin from [https://taku910.github.io/crfpp/](https://taku910.github.io/crfpp/)  
  
check [https://taku910.github.io/crfpp/](https://taku910.github.io/crfpp/) to see how to build and install  
  
source from [https://drive.google.com/drive/folders/0B4y35FiV1wh7fngteFhHQUN2Y1B5eUJBNHZUemJYQV9VWlBUb3JlX0xBdWVZTWtSbVBneU0](https://drive.google.com/drive/folders/0B4y35FiV1wh7fngteFhHQUN2Y1B5eUJBNHZUemJYQV9VWlBUb3JlX0xBdWVZTWtSbVBneU0)

 - 2019-11-26 add CPP interface
   + add `createModel1(const char *)` in `crfpp.h`
   + add `load_model(const char *)` in `tagger.h` `tagger.cpp`
 - 2019-11-27 add CPPP interface
   + add `predict(const char *)` in virtual class `Tagger`
   + add implementation `predict` `parse1` `toString1` in `tagger.cpp`
