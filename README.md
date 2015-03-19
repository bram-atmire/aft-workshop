# aft-workshop
Small sandbox repository for a student workshop

# Procedure for merging

All pull requests have been merged! Here's how:

1. First configure the fetch procedure on your local remote to easily fetch all pending pull requests at once with
bram@Sugarsmooth aft-workshop (master) $ git config --add remote.origin.fetch +refs/pull/*/head:refs/remotes/origin/pr/*
bram@Sugarsmooth aft-workshop (master) $ git fetch origin

2. For each of them, checkout the branch, edit the file to resolve the conflicht, stage the file with "add" and commit to master

bram@Sugarsmooth aft-workshop (master) $ git checkout pr/29
bram@Sugarsmooth aft-workshop (master) $ git merge pr/29 

Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

bram@Sugarsmooth aft-workshop (master|MERGING) $ open README.md 
bram@Sugarsmooth aft-workshop (master|MERGING) $ git add .
bram@Sugarsmooth aft-workshop (master|MERGING) $ git commit -m "PR 29 merged"
[master f0265b1] PR 29 merged

# Names from the exercise

Exercise: Add your name to this list by issuing a pull request

Bram Luyten

azerty

Jense5 (y)

Yanice Slegers

Maaike 

Marnix Michiel Denys

Charlotte

Karlijn Willems

Axel Lemmens

Bram Luyten

Helena Brekalo

FearTheDust

pieterjd

Linus Vanwijck

Robbe Berrevoets

Oscar De Somer

Sven

Cedric Berlanger

Toon Nolten

Roel Storms

Pieter-Jan Van Der Schueren

The one and only Kwinten

Nathan Berghmans

Mr Awesome

Jonah Bellemans

Chuck Norris

Mathias Dekempeneer

Pieter De Wever

MagicalJohn

Xander Deseyn

Vincent Goovaerts
