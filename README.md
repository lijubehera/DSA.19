#Day19ofMyLeetCodeJourney – Problem 349: Intersection of Two Arrays
Today’s challenge was simple but insightful — using set operations to solve problems efficiently!

📘 Problem Summary:
🧾 You're given two integer arrays nums1 and nums2.
 🎯 Your task: Return an array of their intersection – elements that appear in both arrays.
✅ Each element in the result must be unique
 ✅ Order doesn’t matter

💡 Approach:
✅ Pythonic One-Liner using Sets
return list(set(nums1) & set(nums2))
🧠 This uses Python’s set intersection (&) to grab only the common, unique elements.

📌 Why sets?
Automatically removes duplicates
Fast lookup time
Makes the solution super clean

🧪 Example:
Input:
 nums1 = [1, 2, 2, 1]
 nums2 = [2, 2]
 Output: [2]
Input:
 nums1 = [4, 9, 5]
 nums2 = [9, 4, 9, 8, 4]
 Output: [9, 4] or [4, 9]

🧠 What I Learned:
Set operations are powerful for clean and efficient code
For problems involving uniqueness and overlap → always think sets
Simplicity often wins in interviews 🔍
