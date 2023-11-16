# wine reviews dataset
https://www.kaggle.com/datasets/zynicide/wine-reviews/data

# mapper reducer commands
# chmod +x mapper.py
# chmod +x reducer.py

cat word_count_data.txt | python3 mapper.py

cat word_count_data.txt | python3 mapper.py | sort -k1,1 | python3 reducer.py
