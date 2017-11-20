# meetdown

Markdown for meetings

## Use

Replace the **bold** values below with real ones.

### As a participant

1. To join a group, <code>touch groups/<strong>group</strong>/members/<strong>name</strong></code> and create a pull request with the organizer. If the pull request is accepted - congratulations, you are a member!
1. To join a meeting, <code>ln -s groups/<strong>group name</strong>/members/<strong>your name</strong> groups/<strong>group name</strong>/meetings/<strong>date and time</strong>/</code> and create a pull request. You can see where this is going.

### As an organizer

1. To create a meeting, <code>mkdir -p groups/<strong>group name</strong>/meetings/<strong>date and time</strong>/participants</code> and <code>echo <strong>location</strong> > groups/<strong>group name</strong>/meetings/<strong>date and time</strong>/location</code>.
1. You already know how to create a group: <code>mkdir -p groups/<strong>group name</strong>/{meetings,members}</code>

## Advanced use

- Give yourself or the group an alias using `ln -s`.
- Describe yourself in <code>touch groups/<strong>group</strong>/members/<strong>name</strong></code>.
