
 
// learn more about it in the docs: https://pris.ly/d/prisma-schema

 npm install prisma --save-dev
 mongodb+srv://admin:n...2@cluster0.tfxtnuz.mongodb.net/blog_db?retryWrites=true&w=majority

 model Post{
  id String @id @default(auto()) @map("_id") @db.ObjectId
  title String
  description String
  date DateTime @default(now())

}

 npx prisma generate
 npx prisma db push

 npm install @prisma/client
