# Light-switching-program in he room
def move(self):
    self.y += self.speed_y
    self.x += self.speed_x
    self.angle += self.rotation_speed
    if self.y > HEIGHT:
        self.y = random.randint(-100, -40)
        self.x = random.randint(0, WIDTH)

def draw(self, screen):
    rotated_image = pygame.transform.rotate(self.image, self.angle)
    screen.blit(rotated_image, (self.x, self.y))
