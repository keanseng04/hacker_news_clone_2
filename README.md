<div class="container">
<div id="challenge" class="row">
<div class="col-sm-8">
<div class="row">
<div class="col-sm-12">
<div class="tab-content">
<div id="body" class="tab-pane fade in active">

Now we're going to add voting to our Hacker News clone.
<h2>Part 2: Bring on the Votes</h2>
What's Hacker News without voting. Users should be able to up and down vote posts and comments.
<h2>Objectives</h2>
Users should be able to vote up both comments and posts. For now, you can have two separate tables for each type of vote.
<h3>Models &amp; Controllers</h3>
At the very least you should have the following models:
<ol>
	<li><code>Post</code></li>
	<li><code>User</code></li>
	<li><code>Comment</code></li>
	<li><code>PostVote</code></li>
	<li><code>CommentVote</code></li>
</ol>
Don't try to do something fancy and have <code>PostVote</code> and <code>CommentVote</code> inherit from a shared base class. Just have two separate tables and classes for now.
<h3>Views</h3>
Implement all the views and use AJAX to implement the voting.

</div>
</div>
</div>
</div>
</div>
</div>
</div>
&nbsp;
