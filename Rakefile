# Example integration of u3d

task :u3d_install do
  #system("cd ~/Downloads/Unity_Packages/5.6.1f1/; wget -c http://beta.unity3d.com/download/6a86e542cf5c/unity-editor-installer-5.6.1xf1Linux.sh")
  system("u3d install --verbose")
  system("u3d dependencies")
end

task :u3d_load_save_scenes do
  system("u3d -r -- -logFile './editor.log' -executeMethod U3d.EditorRun.LoadSaveScenes -quit -batchmode")
end

task default: %i[u3d_load_save_scenes]

