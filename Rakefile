desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

task :table do
  DB[:conn].execute(sql)
  sql = <<-SQL
  CREATE TABLE IF NOT EXISTS hello (
  hello TEXT,
  hola TEXT,
  nihao TEXT
  );
  SQL
  DB[:conn].execute(sql)
end
