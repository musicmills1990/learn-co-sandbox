Hi! 👋
You've opened the IDE Sandbox. 🎉

The Sandbox is an environment that you can access on "readme" and "code-along" lessons in Learn. It's a great place to experiment with code when you're not working on a "lab" (labs open the IDE In Browser).

The work you do in the Sandbox will be saved from lesson to lesson, and is automatically saved on your behalf to a repository in your GitHub account called `learn-co-sandbox`.

Please DO NOT touch this repository in GitHub, as it will affect your Sandbox experience, and potentially cause your work to be out of sync.

To learn more about the Sandbox, please visit http://help.learn.co/ide-in-browser#sandbox.
function add(x,y){
  return x + y
  }
  
}




function arrayWithinAnotherArray(array,criteriaFn){
  let current = array
  let next = []
  while (current){
    if (criteriaFn(current))
{
      return current
    }
    if
(Array.isArray(current)) {
  for (let i = 0; i < current.length; i++) {
      next.push(current[i])
      }
      }
  }
}
}
  }
}