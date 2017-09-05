# Example integration of u3d

task :u3d_install do
  system("u3d install")
  system("u3d dependencies")
end

task :u3d_load_save_scenes do
  system("u3d -- -logFile './editor.log' -executeMethod U3d.EditorRun.LoadSaveScenes -quit -batchmode")
end

task default: %i[u3d_load_save_scenes]

