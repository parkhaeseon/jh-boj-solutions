This is an archive of problems I have solved in [Baekjoon Online Judge](https://www.acmicpc.net/). For each problem I solved, I will write the summary of the problem, solution sketch, and some additional commentaries if I have any.

# Why did I make this?

* Some of the problems are worth introducing, but is only available in Korean. Some problems are missing their written solutions. I wanted to kill two birds with one stone by creating this archive.
* I wanted to document my problem solving career. I've been personally writing very short summaries for each problem, but sometimes one sentence is not enough to explain the problem or the solution. I expect that by browsing through this repository I would remind myself of the solution much easier.
* I prefer solving problems in a leisurely pace, rather than in a contest setting. In that case, I can write the problem and solution summaries **while** solving the problem! I think it will help me keep the train of thought. Of course, if I'm in a contest, I would not do this because it might waste time.
* I could just upload my source codes, and some people who publish their BOJ solutions do that, but I have never considered it because of the plagiarism issue. Plagiarism is quite a serious issue in BOJ and will result in a penalty or ban.
* TODO

How long will it take to complete the archive? Maybe years. But I'll slowly fill it up.

# Input constraints

I will omit the input ranges that seem less significant. Of course everything in the input must have their maximum sizes specified in the description, but it's too much work to write them all in the archive. (Archiving itself is too much work already...) So if I omit some of the input ranges, you can assume that either long long or long double is enough to solve the problem, and these omitted ranges do not have any meaningful impact on the solution.

For example: suppose I have to solve the maximum subarray sum problem. The size of the array is important because it determines whether O(N^2) passes or not. But I may not specify how large each element in the array can be. In that case, you can assume the elements are small enough that nothing will ever be outside the range of [-2^63, 2^63) during the computation. However, if elements can be extremely large, I must specify that a big integer datatype is required. (Also, the usual O(n) algorithm won't be O(n) anymore, leading to TLE. Can you see why?).
