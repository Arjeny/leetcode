# leetcode
# 830. 较大分组的位置
思考：双指针法，利用快慢指针，start and end，比较两个位置的字符，一样则end++
否则如果end - start >= 3记录，start = end并且end++即可。
