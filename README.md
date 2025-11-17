# reverse-words-in-a-string
class Solution(object):
    def reverseWords(self, s):
        """
        :type s: str
        :rtype: str
        """
        # Split the string by spaces, remove extra spaces, and reverse the words
        words = s.strip().split()
        return " ".join(words[::-1])
